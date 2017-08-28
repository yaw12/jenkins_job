
pipeline {
  agent { any 'ruby' }
  stages {
   stage ('build') {
    steps {
          sh 'ruby --version'
          echo $BUILD_NUMBER
          echo $BUILD_NAME
         }
        }
      }
  }
