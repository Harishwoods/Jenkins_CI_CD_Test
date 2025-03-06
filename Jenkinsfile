pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning the GitHub repository'
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}
