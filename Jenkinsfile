pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh path.sh
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
