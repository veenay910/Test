pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/veenay910/Test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo "Build step complete"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Test step complete"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deploy step complete"'
            }
        }
    }
}