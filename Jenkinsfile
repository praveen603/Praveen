pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/praveen603/Praveen.git'
            }
        }
        stage('Build') {
            steps {
                git 'https://github.com/praveen603/New.git' {
                    sh 'mvn clean compile'
                }
            }
        }
        
    }
}
