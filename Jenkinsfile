pipeline {
  agent {
    docker {
      image 'golang:latest'
    }

  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}