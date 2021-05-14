pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo \'123\''
        git(url: 'http://lan/git/richie_rich.git', poll: true)
      }
    }

  }
}