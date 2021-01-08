pipeline {
  agent any
  stages {
    stage('step1') {
      agent {
        node {
          label 'ss1'
        }

      }
      steps {
        sleep 30
      }
    }

    stage('step2') {
      agent {
        node {
          label 'jk2'
        }

      }
      steps {
        sh 'echo ha'
        sh 'echo ha'
      }
    }

  }
}