pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'jenkins prueva calel'
          }
        }
        stage('') {
          steps {
            emailext(subject: 'correoJenkins', body: 'provando el correo dde jenkins', from: 'calel', to: 'calellopezz@gmail.com')
          }
        }
      }
    }
  }
}