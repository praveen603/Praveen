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
                
                    sh 'mvn clean compile'
                
            }
        }
        
    }
}




