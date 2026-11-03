
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching code from GitHub...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application from GitHub source...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running automated tests...'
            }
        }
    }

    post {
        success {
            echo 'GitHub to Jenkins integration SUCCESS!'
        }
        failure {
            echo 'Pipeline FAILED!'
        }
    }
}
