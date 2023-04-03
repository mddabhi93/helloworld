pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                docker-compose build
            }
        }
    }
}
