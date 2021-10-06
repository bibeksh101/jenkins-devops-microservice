pipeline {
	agent any
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