pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'echo $PATH'
      }
    }

    stage('Test') {
      steps {
        echo 'Test'
        echo 'Test Completed'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}