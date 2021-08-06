pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh '''./mvnw package
java -jar target/*.jar'''
      }
    }

  }
}