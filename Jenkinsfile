#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage('compile stage') {
            steps {
			     withMaven(maven : 'apache-maven-3.5.0'){
                sh 'mvn clean compile'
            }
        }
        stage('Test'){
		  steps {
			     withMaven(maven : 'apache-maven-3.5.0'){
                sh 'mvn test'
            }
           
        }
       
    }
}
