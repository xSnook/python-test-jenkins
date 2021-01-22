node {
    checkout scm

    def customImage = docker.build("python:3.5.1")
    stages {
        stage('build') {
            steps {
                customImage.inside {
                    sh 'python --version'
                }
            }
        }
    }
}
