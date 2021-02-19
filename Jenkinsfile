pipeline {
  agent any
  stages {
    stage('buzz build ') {
      steps {
        sh '''echo "I am a ${BUZZ_NAME}"
'''
        sh '''
echo "I am a ${BUILD_NUMBER}"'''
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
    BUILD_NUMBER = '12'
  }
}