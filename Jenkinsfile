pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        echo 'Compiling'
        sh 'date'
      }
    }

    stage('Testing') {
      steps {
        echo 'I am testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploing'
      }
    }

    stage('Notify') {
      steps {
        echo 'Notificar el deploy'
      }
    }

  }
  environment {
    AUTHOR = 'Albert'
  }
}