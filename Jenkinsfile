pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Neivanny1/curriculum-app', branch: 'master')
      }
    }

    stage('check files') {
      steps {
        sh 'ls -ltr'
      }
    }

  }
}