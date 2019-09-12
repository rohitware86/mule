pipeline {
    agent any 
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