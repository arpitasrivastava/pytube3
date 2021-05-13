pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo \'123\''
        sh 'sudo docker run hello-world'
      }
    }

  }
}