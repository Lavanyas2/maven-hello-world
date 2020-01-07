pipeline {
	agent any
	stages{
		stage('compile stage'){
			steps{
				withmaven(maven : 'apache-maven-3.6.3'){
				bat 'mvn clean compile'
				}
			}
		}
		stage('compile stage'){
			steps{
				withmaven(maven : 'apache-maven-3.6.3'){
				bat 'mvn test'
				}
			}
		}
		stage('deploy stage'){
			steps{
				withmaven(maven : 'apache-maven-3.6.3'){
				bat 'mvn deploy'
				}
			}
		}
	}
}
