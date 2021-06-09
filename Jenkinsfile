pipeline {
    agent any 
    stages {
	
	stage('scm checkout') { 
            steps {
                git clone URL
            }
        }
        stage('Build') { 
            steps {
                mvn package
            }
        }
		  }
        stage('sonar analysis') { 
            steps {
                soanr properties
            }
        }
		
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
