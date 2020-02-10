pipeline {
    agent any
    tools {
        jdk 'jdk-1.8.0_221: C:\Program Files\Java\jdk1.8.0_221\bin '
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
