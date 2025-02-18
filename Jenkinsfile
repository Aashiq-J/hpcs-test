pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('ci') {
      steps {
        sleep 10
        echo 'Hello'
      }
    }

    stage('cd') {
      steps {
        sh 'echo "Hello"'
        sleep 20
      }
    }

  }
}