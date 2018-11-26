#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage('Initilize'){
            stages{
                sh '''
		    echo "stating build"         
       '''
         }
        }
        stage('Build') {
            steps {
                sh 'mvn install' 
            }

        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
