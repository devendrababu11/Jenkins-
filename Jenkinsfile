pipeline {
  agent any
  stages {
    stage ('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage ('addition') {
      steps {
        sh 'python3 addition.py'
      }
    }
  }
}
    
