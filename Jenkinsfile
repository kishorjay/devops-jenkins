pipeline {
		//agent any
	        agent { docker { image: 'maven:3.6.3'}}
		stages{
		stage('Build') {
			steps{
				sh "mvn --version"		
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
