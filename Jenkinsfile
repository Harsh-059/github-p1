pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
    stage('Build') {
      steps {
        sh 'echo Building...'
      }
    }
    stage('Test') {
      steps {
        sh 'echo Testing...'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying...'
      }
    }
  }
  post {
    success { echo 'Pipeline succeeded' }
    failure { echo 'Pipeline failed' }
  }
}
