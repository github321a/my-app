pipeline {
    agent any
    tools {
        jdk 'JDK-1.7'
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
