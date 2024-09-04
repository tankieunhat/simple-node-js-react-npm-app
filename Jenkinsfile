pipeline {
    agent any
    tools {
        nodejs '20.17.0'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}