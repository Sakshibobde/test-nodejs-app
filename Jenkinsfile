pipeline { 
  
   agent any

   stages {
   
     stage('Build') { 
        steps { 
           sh 'Build the application' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
