pipeline { 
  
   agent any
  
   stages {
   
     stage('commit') { 
        steps { 
           sh 'echo "commit..."'
        }
     }
     
     stage('Testing') { 
        steps { 
           sh 'echo "testing application."'
        }
      }
     
     stage('auto-stage') {
        steps {
           sh 'echo "auto-test."'
        }
     }

     stage('deploying') { 
        steps { 
           sh 'echo "deploy application.."'
        }
      }
    }
  
 }
