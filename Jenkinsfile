pipeline {
	agent any
	stages{
		stage('compile stage'){
			steps{
				
				bat 'mvn clean compile'
				
			}
		}
		stage('testing stage'){
			steps{
				
				bat 'mvn test'
				
			}
		}
		stage('deploy stage'){
			steps{
				
				bat 'mvn deploy'
				
			}
		}
	}
}
