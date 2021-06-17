pipeline {
  agent any
  stages {
    stage('gradledep') {
      steps {
        withGradle() {
          sh './gradlew build'
        }

      }
    }

    stage('test') {
      steps {
        sh 'gradlew npm_start'
      }
    }

  }
}