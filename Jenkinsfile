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
        sh 'pwd'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}