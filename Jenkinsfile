pipeline {
  agent any
  stages {
    stage('preparation') {
      steps {
        echo 'preparing'
      }
    }
    stage('auth') {
      steps {
        build 'inject klam'
      }
    }
    stage('test') {
      steps {
        sh 'echo dude'
      }
    }
  }
}
