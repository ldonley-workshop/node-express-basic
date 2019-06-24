pipeline {
  agent any
  stages {
    stage('Npm install') {
      steps {
        sh 'npm install'
        input 'Do you want to test?'
      }
    }
    stage('Test') {
      steps {
        sh 'npm test'
      }
    }
    stage('Build') {
      steps {
        sh 'npm build'
      }
    }
  }
}