//scripted
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// }

// scripted

// node{
// 	echo "Build"
// 	echo "test"
// 	echo "prod"
// }

// declarative

pipeline {
	// agent any  if we donnot use any agent
	agent{ docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps{
				echo "Test"
			}
		}
		stage('Test2') {
			steps{
				echo "Test2"
			}
		}
	}
	
	post{
		always{
			echo "i am awesome"
		}
		success{
			echo "success"
		}
		failure{
			echo "fail"
		}
	}
}
