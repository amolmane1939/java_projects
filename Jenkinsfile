pipeline {
  agent any
  stages {
    stage('version check') {
      agent {
        docker {
          image 'node:16-alpine'
        }

      }
      steps {
        sh 'sh \'node --version\''
      }
    }

  }
}