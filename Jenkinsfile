pipeline {
  agent any
  triggers { githubPush() }
  stages {
    stage('Checkout') {
      steps { checkout scm }
    }
    stage('Show system date') {
      steps { sh 'date' }
    }
  }
}
