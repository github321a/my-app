pipeline {
    agent any
    //tools {
      // jdk 'jdk-1.8.0_221'
      // maven 'Maven-3.6.0'
    //}
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
