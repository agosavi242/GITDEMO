pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        echo 'Cloning repository...'
      }
    }

    stage('Build') {
      agent any
      steps {
        bat 'echo "compliling1"'
      }
    }

    stage('Test') {
      steps {
        echo 'Running tests...'
      }
    }

  }
}