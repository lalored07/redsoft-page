pipeline {
   agent any
   tools {nodejs "nodejs12x"}
   environment{
       CI = 'true'
   }
    stages {
        stage('Build') { 
            steps {
                sh 'npm -version' 
                sh 'npm install'      
            }
        }
        stage('Test'){
            steps{
                sh './jenkins/scripts/test.sh'
            }

        }
        
    }
}