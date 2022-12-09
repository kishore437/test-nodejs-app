pipeline { 
  
   agent any
  
   stages {
   
     stage('git-commit') { 
        steps { 
           sh 'echo "commit..."'
        }
     }
     
     stage('Testing') { 
        steps { 
           sh 'echo "testing application."'
        }
      }
          
     stage('deploying') { 
        steps { 
           sh 'echo "deploy application.."'
        }
      }
    }
  
 }
