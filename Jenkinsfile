pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:20.5.0-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}