pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        java --version
      }
    }
    stage('hello') {
      steps {
        java reon.java
      }
    }
  }
}
