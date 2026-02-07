pipeline {
    agent any

    environment {
        APP_ENV = 'dev'
    }

    stages {

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application v2'
            }
        }
    }

    post {
        success {
            echo 'CI/CD Pipeline Successful'
        }
        failure {
            echo 'CI/CD Pipeline Failed'
        }
    }
}
