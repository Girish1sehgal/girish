pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Client Tests') {
            steps {
                dir('sample-node-project') {
                    sh 'npm install'
                    sh 'npm test'
                }
            }
        }
    }
}
