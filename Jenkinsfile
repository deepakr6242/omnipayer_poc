pipeline {
  agent any
  stages {
    stage('Clone and deploy') {
      steps {
        sh '''cd C:\\Users\\omniadmin\\Desktop\\
set PATH=C:\\Program Files\\Git\\bin;%PATH%
python deploy.py
exit'''
      }
    }
  }
}