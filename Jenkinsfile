pipeline {
    agent any
    environment {
        COMPOSE_PROJECT_NAME = "${env.JOB_NAME}-${env.BUILD_ID}"
    }
    stages {
        ....  your stages go here ....
    }
    post {
        always {
            sh "docker-compose down -v"
        }
    }
}
