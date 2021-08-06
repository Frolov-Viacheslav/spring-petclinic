pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell(script: 'mvn package', encoding: 'utf-8')
      }
    }

  }
}