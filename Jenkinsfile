pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                cmd.exe 'mvn compile'
            }
        }
        stage('test') {
            steps { 
                cmd.exe 'mvn test'
            }
        }
        stage('package') {
            steps { 
                cmd.exe 'mvn package'
            }
        }
    }
}
