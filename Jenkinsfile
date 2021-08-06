pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat './mvnw package &&  java -jar target/*.jar'
      }
    }

  }
}