pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ws(dir: 'pg_amqp') {
          sh 'make'
        }

      }
    }
  }
}