pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        withGradle() {
          sh 'git --vers'
        }

      }
    }

  }
}
