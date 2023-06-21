pipeline {
  agent any
  options { 
    checkoutToSubdirectory('/var/lib/jenkins/workspace/pipe100/dir100') 
   } 
  stages {
    stage("build") {
       steps {
         sh 'echo hello'
      }
   }
  }
}

