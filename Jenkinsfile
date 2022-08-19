pipeline {
  agent any
  stages {
    stage('Reconstruir') {
      steps {
        build(job: 'asd', propagate: true, wait: true, quietPeriod: 6)
      }
    }

    stage('Ejecutar comando') {
      steps {
        sh 'll'
      }
    }

    stage('Mail') {
      steps {
        mail(subject: 'dsd', body: 'sdsad')
      }
    }

    stage('End') {
      steps {
        echo 'Termine'
      }
    }

  }
}