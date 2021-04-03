pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh "docker stop node && docker rm node"
        sh "docker stop mongo && docker rm mongo"
        sh "docker-compose up -d"
      }
    }
  }
}
