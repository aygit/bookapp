pipeline {
  agent any

  stages {
    stage('Build') {
         steps {
         sh   'npm install'
        }
   }
 

   stage('Deploy') {
    steps  {
      sh  './jenkins/scripts/deploy.sh'
      echo ' app has been deplloyed successfully'

    }

  }

} 

} 
