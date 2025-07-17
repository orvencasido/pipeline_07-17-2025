pipeline {
	agent any

	environment {
		NAME="Orven"
	}

	stages {
		stage('Build'){
			steps{
				sh '''
					echo "Hello $NAME"
				'''
			}
		}
	}
}
