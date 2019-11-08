pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'jenkins prueva carlos'
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
