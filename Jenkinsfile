pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/sinchana082005/CICD_Task1.git'
            }
        }

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