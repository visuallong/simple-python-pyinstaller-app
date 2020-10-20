pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'This is mini pipeline.'
        sh 'python -V'
      }
    }

    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Test') {
      steps {
        echo 'Test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
  environment {
    python = '/var/lib/'
  }
}