pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello'
          }
        }

        stage('Build2') {
          steps {
            echo 'Hello my india'
          }
        }

        stage('message') {
          steps {
            echo 'Hello message'
          }
        }

      }
    }

  }
}