node{
	stage('Build'){
		echo "Build"
	}
	stage('Test'){
		echo "Test"
	}
}

post{
	always{
		echo "I always run"
	}
	success{
		echo "I run when Success"
	}
	failure{
		echo "Stage Failure"
	}
	changed{
		echo "Stage Changed"
	}
}