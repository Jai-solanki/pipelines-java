pipeline {
  agent any
  stages {
    stage('buzz build ') {
      parallel {
        stage('Testing A') {
          steps {
            sh '''echo "I am a ${BUZZ_NAME}"
'''
            sh '''
echo "I am a ${BUILD_NUMBER}"'''
          }
        }

        stage('Testing B') {
          steps {
            sh '''sleep 10
echo done.'''
          }
        }

      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
    BUILD_NUMBER = '12'
  }
}