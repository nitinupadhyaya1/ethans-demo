pipeline {
agent any
stages {
	stage('SCM') {
			steps {
				echo "SCM from webhook"
				}
				}
	stage('Testing') { 
			steps {
				echo "Testing the code"
				}
				}
	stage('Deploying') {
			steps {
				echo "Deploying the code in production"
					}
					}
	stage('Validation') {
			steps {
				echo "Validation the code deployed in Production..."
					}
					}
	stage('Post Validation') {
		steps {
				echo "This is post validation for support team to verify if everything is working as expected..."
		}
	}
		}
		}
