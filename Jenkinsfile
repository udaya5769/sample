pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        script {
          def sonarscanner = tool(name: 'sonarscanner4', type: 'hudson.plugins.sonar.SonarRunnerInstallation')
          tool(name: 'maven-3', type: 'maven')
          sh "${sonarscanner}/bin/sonar-scanner --version"
        }

      }
    }

  }
}