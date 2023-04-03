pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                sh ...
                  docker compose version
                  docker-compose build
            }
        }
    }
}
