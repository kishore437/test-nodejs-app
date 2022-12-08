pipeline { 
  
   agent any

   stages {
   
     stage('commit') { 
        steps { 
           sh 'echo "commit..."'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application."'
        }
      }
     
     stage('deploy') { 
        steps { 
           sh 'echo "deploy application..."'
        }
      }
   }
   }
