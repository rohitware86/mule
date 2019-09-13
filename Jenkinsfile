pipeline {
    agent any
    withMaven(maven: 'maven-3')
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
    	stage('Unit Test') { 
     		 steps {
        		sh 'mvn clean test'
      		}
        }
    }
}