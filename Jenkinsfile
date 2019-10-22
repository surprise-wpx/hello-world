pipeline {
  agent {
    node {
      label 'DEMO_NODE'
    }

  }
  stages {
    stage('DEMO') {
      agent {
        node {
          label 'DEME_NODE'
        }

      }
      steps {
        sh 'echo test'
      }
    }
  }
}