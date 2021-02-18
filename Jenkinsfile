pipeline {
  agent any
  stages {
    stage('buzz build ') {
      steps {
        echo 'hello'
      }
    }

    stage('buzz test') {
      steps {
        junit '**/surefire-reports/**/*.xml'
      }
    }

  }
}