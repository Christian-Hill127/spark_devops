pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('Mvn Class') {
      steps {
        sh 'mvn package -DskipTests'
      }
    }
  }
}