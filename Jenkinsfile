pipeline {
	agent any
	stages{
		stage('compile stage'){
			steps{
				withmaven(maven : ''){
				bat 'mvn clean compile')
				}
			}
		}
		stage('compile stage'){
			steps{
				withmaven(maven : ''){
				bat 'mvn test')
				}
			)
		}
		stage('deploy stage'){
			steps{
				withmaven(maven : ''){
				bat 'mvn deploy')
				}
			)
		}
	}
}
