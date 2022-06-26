pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build this application'
          }
        }

        stage('Deploy ') {
          steps {
            echo 'deploy this application'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test this application'
      }
    }

  }
}