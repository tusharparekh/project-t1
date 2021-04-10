#!groovy

pipeline {
  agent none
  stages {
    
    stage('Docker Build') {
      agent any
      steps {
        bat 'docker build -t nginx/alpine:latest .'
      }
    }
    stage('Docker Run') {
      agent any
      steps {
        bat 'docker run -p 8084:80 nginx/alpine'
      }
    }
  }
}
