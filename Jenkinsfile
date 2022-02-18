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
        pwd(tmp: true)
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}