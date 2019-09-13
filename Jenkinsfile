pipeline {
    agent any
    tools {
        maven 'Maven 3.2.5'
    }
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