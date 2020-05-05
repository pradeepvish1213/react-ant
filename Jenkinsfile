pipeline {
    agent any
    stages {
        stage('Information') {
            steps {
                sh 'npm --version'
            }
        }
        stage('Installing') {
            steps {
                sh 'npm install'
            }
        }
        stage('Start Server') {
            steps {
                sh 'npm start'
            }
        }
    }
}
