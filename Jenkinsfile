pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                bat label: 'Version', script: 'npm -v'
            }
        }
        stage('Installing') {
            steps {
                bat label: 'Installing npm', script: 'npm install'
            }
        }
        stage('Start Server') {
            steps {
                bat label: 'Start Server', script: '\node_modules\.bin\pm2 start'
            }
        }
    }
}
