pipeline {
    agent none
    stages {
        stage('build') {
			agent {
				docker {
					image 'python:2-alpine'
				}
			}
            steps {
                sh 'python --version'
            }
        }
    }
}