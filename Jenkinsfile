pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                exe 'mvn compile'
            }
        }
        stage('test') {
            steps { 
                exe 'mvn test'
            }
        }
        stage('package') {
            steps { 
                exe 'mvn package'
            }
        }
    }
}
