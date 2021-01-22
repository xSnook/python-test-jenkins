pipeline {
    environment {
        HTTP_PROXY  = 'internet.ford.com:83'
        HTTPS_PROXY = 'internet.ford.com:83'
    }
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
