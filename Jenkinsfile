pipeline {
  agent any
  stages {
    stage('gradledep') {
      steps {
        withGradle()
        withGradle() {
          sh './gradlew build'
        }

      }
    }

  }
}