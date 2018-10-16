pipeline {
  agent any
  stages {
    stage('Clone and deploy') {
      steps {
        echo 'Hello'
      }
    }
    stage('get Commits') {
      steps {
        bat(script: 'python  em@il.py', returnStatus: true, returnStdout: true)
      }
    }
  }
}