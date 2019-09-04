pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd rt_test
make'''
      }
    }
  }
}