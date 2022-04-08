pipeline {
    agent any
    tools {
      //jdk 'jdk-1.8.0_221'
       maven 'M3'
    }
    stages {
        stage('--clean--') { 
            steps {
                bat "mvn clean"
            }
        }
        stage('--Test--') { 
            steps {
                bat "mvn test"
            }
        }
        stage('--Package--') { 
            steps {
                bat "mvn package"
            }
        }
    }
}
