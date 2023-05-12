pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
      }
    }

    stage('Clone') {
      steps {
        git(url: 'https://github.com/pgorzkowicz/demo', branch: 'main')
      }
    }

  }
}