pipeline {
  agent any
  stages {
    stage('one') {
      parallel {
        stage('one') {
          steps {
            sh 'ls'
          }
        }
        stage('one1') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('two') {
      steps {
        echo 'ok'
      }
    }
    stage('') {
      steps {
        echo 'finish'
      }
    }
  }
}