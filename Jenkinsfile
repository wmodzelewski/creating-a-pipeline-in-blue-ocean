pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('can') {
      steps {
        input(message: 'qq', id: 'ww', ok: 'sss88')
      }
    }
  }
}