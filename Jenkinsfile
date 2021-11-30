pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                powershell 'mvn compile'
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
