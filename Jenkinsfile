pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Hello world'
                sh "docker-compose build . -t mahesh/helloworld:latest"
                echo 'Build Successfully'
            }
        }
    }
}
