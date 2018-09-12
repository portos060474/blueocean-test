pipeline {
  agent none
  stages {
    stage('preparation') {
      steps {
        echo 'preparing'
      }
    }
    stage('auth') {
      steps {
        build 'test-klam'
      }
    }
  }
}