pipeline {
    agent any
    tools {
      jdk 'JAVA'
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
