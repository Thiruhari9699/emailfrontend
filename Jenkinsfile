pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
              echo 'building the application...'
              echo 'application built...'  
            }
        }
      stage('test') {
            steps {
               echo 'testing the application...'
            }
      }
      stage('deploy') {
            steps {
               echo 'deploting the application...'
            }
      }
    }
}
