pipeline {
  agent any
  stages {
    stage('Change Check') {
      steps {
        git(url: 'https://github.com/rakeshthyd/jenkins', branch: 'master')
      }
    }

    stage('Print Message') {
      steps {
        echo 'Hello World !!!'
      }
    }

  }
}