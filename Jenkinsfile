//pipline for testing with jest
node {
    stage('test') {
        steps {
        sh 'npm install --save-dev jest',
        sh 'npm run test'
        }
    }

    stage('build') {
        steps {
        sh 'npm run build'
        }
    }

    stage('deploy') {
        steps {
        sh 'npm run deploy'
        }
    }
}