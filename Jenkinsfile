pipeline{
    agent {
        label "docker-agent"
    }
    stages {
        stage ("build docker container") {
            steps {
                sh 'sudo docker-compose up -d'
            }
        }
    }
}