pipeline {
	agent{
		docker{
			image 'maven:3.6.3'
		}
	}
	stages {
		stage('Build'){
			steps{
				sh 'mnv --version'
				sh 'docker --version'
			}
		}
		stage('Docker'){
			steps{
				sh 'which docker'
			}
		}
	}
}