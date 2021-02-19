pipeline {
  agent any
  stages {
    stage('Deploying ') {
      agent any
      environment {
        Hii_Name = 'hello'
      }
      steps {
        input(message: 'Deploy to stage', ok: 'please to it ')
        sh 'printenv'
      }
    }

  }
  environment {
    Hii_Name = 'hello'
  }
}