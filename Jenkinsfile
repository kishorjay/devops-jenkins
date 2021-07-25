pipeline {
		agent any
		stages{
		stage('Build') {
			steps{
						echo "Build"
			}
		}
		stage('Test') {
			steps{
						echo "Test"
			}
		}
		stage('QA Test') {
			steps{
						echo "QA Test"
			}
		}
	}
	post{
		always{
		echo "i always run"
		}
		success{
		echo "i always on success"
		}
		failure{
		echo "i always on failure"
		}
	
	}
}
