pipeline {
	agent any

	tools {nodejs "mernstack"}

	stages {
		stage('Checkout') {
			steps {
				checkout scm
			}
		}
	

	stage('Client Tests') {
	steps {
			sh 'npm install'
			sh 'npm test'
		}
	}
}
}
