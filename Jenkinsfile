pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'mymaventrade'
      }
    }
    stage('SIT') {
      steps {
        echo 'hello build sucessfull'
      }
    }
  }
}