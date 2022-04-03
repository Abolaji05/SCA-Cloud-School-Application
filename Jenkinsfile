pipeline {

    agent any
    stages {
        stage('Building code') {
      steps {
        sh 'python3 sca.py'
          }
        }
    
    stage('Success message') {
      steps {
        sh 'echo "Yes it works"'
      }
    }

    }
}
