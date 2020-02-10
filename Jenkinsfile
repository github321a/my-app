pipeline {
    agent any
    //tools {
      // jdk 'jdk-1.8.0_221'
      // maven 'Maven-3.6.0'
    //}
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
