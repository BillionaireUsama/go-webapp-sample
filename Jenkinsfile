pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        powershell 'go test ./...'
      }
    }

  }
}