pipeline {

   agent { 
       dockerfile true 
    }

   tools {
       nodejs "nodejs12x"
    }

    environment{
       CI = 'true'
   }

    stages {
        /*stage('Build') { 
            steps {
                sh 'npm -version' 
                sh 'npm install'      
            }
        }*/
        stage('Front-end') {
            steps {
                sh 'node --version'
            }
        }                
        
    }
}