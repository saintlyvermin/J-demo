pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        'javac HelloWorld.java'
      }
    }
    stage('run') {
      steps {
        'java HelloWorld'
      }
    }
  }
}
