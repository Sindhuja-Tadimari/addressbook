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
                powershell 'mvn test'
            }
        }
        stage('package') {
            steps { 
                powershell 'mvn package'
            }
        }
    }
}
