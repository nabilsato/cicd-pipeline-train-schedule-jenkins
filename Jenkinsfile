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

  }
}