pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'java --version'
      }
    }
    stage('hello') {
      steps {
        sh 'java reon.java'
      }
    }
  }
}