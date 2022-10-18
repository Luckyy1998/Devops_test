pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "Hello Stage1"'
          }
        }

        stage('Stage1.1') {
          steps {
            sh 'echo "Hello stage1.1"'
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        sh 'echo "Hello Stage2"'
      }
    }

  }
}