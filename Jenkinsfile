pipeline {
  agent any
  stages {
    stage('testing') {
      environment {
        BROWSERSTACK_USERNAME = 'hiteshraghuvansh2'
        BROWSERSTACK_ACCESS_KEY = 'qyZKtjHYVnhsougiNxYD'
      }
      steps {
        sh 'mvn test -P single'
      }
    }
  }
}