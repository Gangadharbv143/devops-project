pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Gangadharbv143/devops-project.git'
            }
        }
        stage('Print Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
