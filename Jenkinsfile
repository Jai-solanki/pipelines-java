pipeline {
  agent any
  stages {
    stage('buzz build ') {
      steps {
        echo 'echo'
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

  }
}