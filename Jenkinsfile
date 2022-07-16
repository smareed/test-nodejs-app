pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
          sh 'echo "Installing Dependencies..."'
          sh 'uptime'
          sh 'hostname'
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
