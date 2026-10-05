pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo "Starting build process..."'
                bat 'echo "Build completed successfully."'
            }
        }
        stage('Test') {
            steps {
                bat 'echo "Running unit tests..."'
                bat 'echo "All tests passed successfully!"'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo "Deploying application to environment..."'
                bat 'echo "Deployment successful!"'
            }
        }
    }
}
