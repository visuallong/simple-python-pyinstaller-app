pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'This is mini pipeline.'
        sh 'python -V'
        sh '''apt-get install python3.7
python3 -V'''
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