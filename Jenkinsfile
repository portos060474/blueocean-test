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
        build 'inject klam'
      }
    }
    stage('test') {
      steps {
        sh 'aws ec2 describe-instances --region eu-west-1'
      }
    }
  }
}