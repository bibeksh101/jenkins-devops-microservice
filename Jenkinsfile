pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				sh 'mvn --version'
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