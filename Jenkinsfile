pipeline{
    agent any
    stages {
        stage ("build docker container") {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}