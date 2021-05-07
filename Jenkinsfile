pipeline {
  agent {
    docker {
      image 'lan:10000/base:latest'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'echo \'123\''
      }
    }

  }
}