pipeline { 
  
   agent any

   stages {
   
     stage('build') { 
        steps { 
           echo 'build the application'
        }
     }
     
     stage('Test') { 
        steps { 
            echo "testing application..."
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           echo "deploying application..."
         }

     }
  
   	}
