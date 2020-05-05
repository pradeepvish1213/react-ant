pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat label: 'Installing npm', script: 'npm install'
            }
        }
    }
}
