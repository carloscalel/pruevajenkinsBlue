pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'jenkins prueva carlos123'
          }
        }
        stage('error') {
          steps {
            echo 'hola calell '
          }
        }
      }
    }
  }
}