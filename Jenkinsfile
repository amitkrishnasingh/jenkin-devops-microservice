
//DECLARATIVE
pipeline {
	//agent any
	agent {docker {image 'maven:3.6.3'} }
	stages {
		stage('build') {
			steps {
			sh 'maven --version'
			echo "build"	
			}
		}
		stage('test') {
			steps {
			echo "test"	
			}
		}
		stage('integration test') {
			steps {
			echo "integration test"	
			}
		}
	}
	post {
		always {
			echo "main wo unhoni hoon jo koi taal nai sakta! haaahaaa"
		}
		success {
			echo "Avengers, Assemble!"
		}
		failure {
			echo "I know you could do better than that !"
		}
		//changed {
		//	echo "mail dev to fix build"
		//}
	}

}

