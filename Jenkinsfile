pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo Hello Welcome'
        tool(name: 'sonarscanner4', type: 'hudson.plugins.sonar.SonarRunnerInstallation')
        tool(name: 'maven-3', type: 'maven')
        sh 'sonar-scanner --version'
      }
    }

  }
}