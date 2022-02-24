pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo Hello Welcome'
        tool 'sonarscanner4'
        tool 'maven-3'
      }
    }

  }
}