pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'java --version'
      }
    }
    stage('hello') {
      steps {
        bat 'java reon.java'
      }
    }
  }
}
