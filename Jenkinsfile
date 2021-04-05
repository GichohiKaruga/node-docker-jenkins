pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh "docker-compose down -d"
        sh "docker-compose up -d"
      }
    }
  }
}
