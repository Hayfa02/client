pipeline {
  agent any
    stages {
    
    
      stage("build") {
        steps {
          sh 'ng build'
          sh 'ng serve'
          }
        }
        
           
      stage("test") {
        steps {
          echo 'testing the application...'
        }
      }
      
              
      stage("deploy") {
        steps {
          echo 'deploying the application...'
        }
      }
      
    
      
    }
  }
      
      