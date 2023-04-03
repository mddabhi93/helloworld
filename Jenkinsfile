pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Hello world'
                docker-compose build
                echo 'Build Successfully'
            }
        }
    }
}
