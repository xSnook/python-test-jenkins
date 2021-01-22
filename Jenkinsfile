pipeline {
    agent { 
        docker { 
            image 'python:3.5.1'
            args '-v C:\\Users\\shill136\\.jenkins\\workspace\\python-test_main:C:\\Users\\shill136\\.jenkins\\workspace\\python-test_main'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
