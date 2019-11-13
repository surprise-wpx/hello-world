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
  }
}