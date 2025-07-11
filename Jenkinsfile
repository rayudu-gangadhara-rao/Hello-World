pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning code from GitHub"
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo "Simulating build"
                sh 'echo Building app...'
            }
        }

        stage('Test') {
            steps {
                echo "Simulating test"
                sh 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo "Simulating deployment"
                sh 'echo Deploying to server...'
            }
        }
    }
}
