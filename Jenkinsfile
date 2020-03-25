pipeline {
    agent any
 
    tools {nodejs "node"}
 
    stages {
 
        stage('Cloning Git') {
            steps {
                git 'https://github.com/gigue2022/chitchat'
            }
        }
 
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }
 
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}
