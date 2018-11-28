pipeline {
    agent any 
    stages {
        stage('Clone Repo') {
            steps {
                sh "mvn clean"
                
            }
        }
        stage('Test Project') {
            steps {
                sh "mvn test "
                
            }
        }
        stage('Deploy') {
            steps {
                sh "mvn package"
                
            }
        }
    }
}
