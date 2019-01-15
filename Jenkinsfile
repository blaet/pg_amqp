pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        ws(dir: 'pg_amqp') {
          sh '''

apt-get update && apt-get install 

build-essentials && make'''
        }

      }
    }
  }
}