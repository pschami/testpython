pipeline {
  agent any
  stages {
    stage('Welcome') {
      steps {
        echo 'Welcome to Jenkins'
      }
    }
    stage('Readme') {
      steps {
        sh 'cat README.md'
      }
    }
  }
}