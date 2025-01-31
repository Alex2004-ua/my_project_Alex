pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Alex2004-ua/my_project_Alex.git'
            }
        }
        
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building project"'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }
        
        stage('Deploy') {
            steps {
                sh 'echo "Deploying"'
            }
        }
    }
}
