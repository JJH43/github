pipeline {
  agent none
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo hello'
          }
        }

        stage('build 2') {
          steps {
            sh 'echo hello 2'
          }
        }

      }
    }

  }
}