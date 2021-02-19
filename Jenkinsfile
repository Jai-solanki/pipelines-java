pipeline {
  agent any
  stages {
    stage('buzz build ') {
      steps {
        sh 'echo "I am a ${BUZZ_NAME}"'
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}