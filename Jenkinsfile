pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Hello world'
                sh "docker-compose build"
                echo 'Build Successfully'
            }
        }
    }
}
