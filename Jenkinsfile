pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/praveen603/Praveen.git'
            }
        }
		tools{
		    maven 'Maven3.1.1'
			jdk'java8'
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




