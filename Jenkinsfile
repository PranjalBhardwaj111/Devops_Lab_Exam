pipeline {
  agent any
  stages {
      stage('Testing'){
        steps{
          echo 'running Tests'
          echo 'Command 1'
        }
      }
      stage('Build') {
        steps{
          sh 'python3 app.py'
        }
      }
  }
}    
