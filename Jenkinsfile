pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello World!'
      }
    }

    stage('Second') {
      steps {
        input(message: 'Deploy to QA?', ok: 'Yes')
        echo 'Hello Girish'
      }
    }

  }
}