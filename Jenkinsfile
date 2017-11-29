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
                
                    echo 'Build step'
                
            }
       	   }
		   stage('Test'){
	       steps {
		   echo 'Test step'
	   }
	   }
       
	   stage('Deploy'){
	       steps {
		   echo 'deploy step'
	   }
	   }
	   
	   
    }
}




