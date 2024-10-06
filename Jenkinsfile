pipeline {
  agent any
  stages {
    stage('Clone Repository') {
      steps {
        git 'https://github.com/dth99/simple-node-js-react-npm-app.git'
      }
    }
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh 'npm test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }
  }
}
