pipeline {
  agent any
  stages {
    stage('gradledep') {
      steps {
        withGradle() {
          sh 'gradelw'
        }

      }
    }

  }
}