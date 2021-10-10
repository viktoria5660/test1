pipeline {
  agent {
    docker {
      image 'node:14-alpine'
    }

  }
  stages {
    stage('init') {
      steps {
        sh 'npm --version'
      }
    }

  }
}