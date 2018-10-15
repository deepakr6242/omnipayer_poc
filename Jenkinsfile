pipeline {
  agent any
  stages {
    stage('Get source') {
      steps {
        sh '''cd C:\\Users\\omniadmin\\Desktop\\
set PATH=C:\\Program Files\\Git\\bin;%PATH%
python deploy.py
exit'''
      }
    }
  }
}