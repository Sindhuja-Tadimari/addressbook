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
                emailext body: '${BUILD_NUMBER)', subject: 'The build has completed with status as ${BUILD_STATUS}', to: 'tadimarisindhuja@gmail.com'
            }
        }
    }
}
