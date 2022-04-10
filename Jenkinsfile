pipeline {
    agent any
    tools {
      jdk 'JAVA'
       maven 'M3'
    }
    stages {
        stage('--clean--') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('--Test--') { 
            steps {
                sh "mvn test"
            }
        }
        stage('--Package--') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
