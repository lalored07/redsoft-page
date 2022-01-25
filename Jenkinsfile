pipeline {
   agent any
   tools {nodejs "nodejs12x"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm -version' 
                sh 'npm install'      
            }
        }
    }
}