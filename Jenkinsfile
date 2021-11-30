pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                CMD.EXE'mvn compile'
            }
        }
        stage('test') {
            steps { 
                CMD.EXE'mvn test'
            }
        }
        stage('package') {
            steps { 
                CMD.EXE'mvn package'
            }
        }
    }
}
