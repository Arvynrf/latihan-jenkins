pipeline{
    agent any
    stages {
        stage ("build docker container") {
            steps {
                sh 'sudo docker-compose up -d'
            }
        }
    }
}