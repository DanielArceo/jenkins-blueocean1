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

  }
  environment {
    AUTHOR = 'Albert'
  }
}