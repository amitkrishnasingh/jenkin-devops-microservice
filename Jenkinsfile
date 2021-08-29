
//DECLARATIVE
pipeline {
	agent any
	stages {
		stage('build') {
			steps {
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
			echo "I know you could do better than that!"
		}
	}

}

