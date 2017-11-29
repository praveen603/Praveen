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
                maven 'C/apache-maven-3.5.0/my-app' {
                    sh 'mvn clean compile'
                }
            }
        }
        
    }
}
