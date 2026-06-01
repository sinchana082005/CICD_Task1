pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t cicd-task1 .'
            }
        }

        stage('Verify Docker Image') {
            steps {
                bat 'docker images'
            }
        }
    }
}
