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
	agent any
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
}
