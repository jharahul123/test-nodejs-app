 pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies asap') { 
        steps { 
         echo 'building the applications'
           //sh 'npm install' /
        }
     }
     
     stage('Test') { 
        steps { 
         echo 'testing the applications'
           //sh 'echo "testing application..."'//
        }
      }

         stage("Deploy application") { 
         steps { 
          echo 'deploying the applications'
           //sh 'echo "deploying application..."'//
         }

     }
  
   	}

   }
