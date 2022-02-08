pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Testing'
          }
        }

        stage('') {
          steps {
            echo 'valid'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        sleep 10
      }
    }

  }
}