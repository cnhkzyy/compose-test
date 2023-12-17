pipeline {
  agent any
  stages {
    stage('stage 1: start server') {
      steps {
        sh 'docker-compose up'
        sh '''curl 192.168.1.5:5000
echo \'tested completed!\''''
      }
    }

  }
}