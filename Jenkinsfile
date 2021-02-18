pipeline {
  agent any
  stages {
    stage('buzz build ') {
      steps {
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
        sh './jenkins/build.sh'
      }
    }

  }
}