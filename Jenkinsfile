pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/hexacyanide/aptmt-dashboard.git', branch: 'jenkins-ci')
      }
    }
    stage('test') {
      steps {
        sh 'ls'
      }
    }
  }
}