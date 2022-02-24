pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo Hello Welcome'
        tool 'sonarscanner4'
        tool(name: 'maven-3', type: 'maven')
      }
    }

  }
}