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
        sh '''sonar-scanner \\
  -Dsonar.projectKey=SonarQube \\
  -Dsonar.sources=. \\
  -Dsonar.host.url=http://localhost:9000 \\
  -Dsonar.login=0cea422d287c159a34a87d67fde555818aab1e31'''
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}