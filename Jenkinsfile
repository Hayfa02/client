pipeline {
  agent any
    stages {
      
      
        stage("slack") {
         steps {
           slackSend color: '#439FE0' , message:'test message'
          }
        }
    
    
      stage("build") {
        steps {
          sh 'ng build '
          sh ' ng serve  '
          }
        }
      
      
        
        
      
              
  
      
    }
  }
      
      
