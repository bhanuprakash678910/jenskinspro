pipeline {
 agent any
 stages {
   stage("git init"){
     steps {
       checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/bhanuprakash678910/mavenproj.git']])
    }
   }
 }
}

