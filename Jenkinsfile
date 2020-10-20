pipeline {
  agent none
  stages {
    stage('Initialize') {
      steps {
        echo 'This is mini pipeline.'
        sh 'python -v'
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
}