pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            sleep 3
          }
        }
        stage('fsfa') {
          steps {
            echo '333'
          }
        }
      }
    }
    stage('g1') {
      parallel {
        stage('g1') {
          steps {
            sleep 3
          }
        }
        stage('g214') {
          steps {
            echo '4343'
          }
        }
      }
    }
  }
}