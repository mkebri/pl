pipeline {
  agent any
  stages {
    stage('Preparation') {
      parallel {
        stage('Preparation') {
          steps {
            sh 'ls -l '
          }
        }

        stage('Verification') {
          steps {
            echo 'Tout est OK'
          }
        }

      }
    }

    stage('Build') {
      steps {
        sleep 3000
      }
    }

  }
}