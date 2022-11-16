pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        script {
          'javac HelloWorld.java'
        }
      }
    }
    stage('run') {
      steps {
        script {
          'java HelloWorld'
        }
      }
    }
  }
}
