pipeline{
    agent any
    stages {
        stage ("build docker container") {
            steps {
                bat 'sudo docker-compose up -d'
            }
        }
    }
}