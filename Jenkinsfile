pipeline {
  agent none
  stages {
    stage('Initialize') {
      steps {
        echo 'This is mini pipeline.'
      }
    }

    stage('Build') {
      steps {
        sh 'echo \'Build\''
      }
    }

    stage('Test') {
      steps {
        sh 'echo \'Test\''
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo \'Deploy\''
      }
    }

  }
}