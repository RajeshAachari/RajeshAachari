pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "stage 1"'
          }
        }

        stage('pipeline 1') {
          steps {
            sh 'echo " pipeline 1"'
          }
        }

      }
    }

    stage('stage 2') {
      steps {
        sh 'echo "stage 2"'
      }
    }

  }
}