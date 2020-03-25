pipeline {
    agent any
 
    tools {nodejs "node"}
 
    stages {
 
        stage('Cloning Git') {
            steps {
                git 'https://github.com/<your_name>/<your_repo>'
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
