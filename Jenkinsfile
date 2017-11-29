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
                maven 'https://github.com/praveen603/New.git' {
                    sh 'mvn clean compile'
                }
            }
        }
        stage('Deploy') {
            steps {
                withMaven(maven: 'maven_3_0_5') {
                    sh 'mvn deploy'
                }
            }
        }
    }
}
