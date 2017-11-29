pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/praveen603/Praveen.git'
            }
        }
		tools{
		    maven 'C/apache-maven-3.5.0'
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




