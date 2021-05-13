pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo \'123\''
        sh 'docker run hello-world'
      }
    }

  }
}