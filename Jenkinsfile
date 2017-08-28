pipeline {
  agent { docker}
  stages {
   stage ('build') {
    steps {
          sh 'git --version'
          echo $BUILD_NUMBER
          }
        }
      }
  }
