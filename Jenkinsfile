pipeline {
    agent {
        node {
            label 'docker-agent'
        }
    }
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the GitHub repository
                git 'https://github.com/ChoudharyNarendra/Jenkins-Docker-Github.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build steps here (e.g., compiling code, installing dependencies)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your testing steps here (e.g., running unit tests)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add your deployment steps here (e.g., pushing to a server, deploying to a cloud service)
            }
        }
    }
}
