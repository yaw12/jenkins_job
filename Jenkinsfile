pipeline {
  agent { docker 'ruby' }
  stages {
   stage ('build') {
    steps {
          sh 'ruby --version'
          echo $BUILD_NUMBER
          }
        }
      }
  }
