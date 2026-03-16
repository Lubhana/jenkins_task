pipeline {
    agent any

    stages {

        stage('Pull from Git') {
            steps {
                echo "Repository pulled successfully"
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Tests successful'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo Deployment successful'
            }
        }
    }
}
