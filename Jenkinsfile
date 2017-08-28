pipeline {
  agent { master }
  stages {
   stage ('build') {
    steps {
          sh 'git --version'
          echo $BUILD_NUMBER
          }
        }
      }
  }
