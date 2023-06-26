pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''stage(\'Client Tests\') {
	steps {
		dir(\'client\') {
			sh \'npm install\'
			sh \'npm test\'
		}
	}
}'''
        }
      }

    }
  }