pipeline {
  agent any
  stages {
    stage('stage 1: start server') {
      steps {
        sh 'docker-compose up -d'
        sh '''curl 192.168.1.5:5000
echo "test completed"'''
      }
    }

  }
}