//pipline for testing with jest
node {
    stage('test') {
        sh 'npm install --save-dev jest'
        sh 'npm run test'
    }

    stage('build') {
        sh 'npm run build'
    }

    stage('deploy') {
        sh 'npm run deploy'
    }
}