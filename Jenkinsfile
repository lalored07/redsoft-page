pipeline {
    agent { label 'nodejs12x' }
    stages {
        stage('Build') { 
            steps {
                sh 'npm -version' 
                sh 'npm install' 
            }
        }
    }
}