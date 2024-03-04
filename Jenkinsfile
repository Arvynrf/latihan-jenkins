pipeline{
    agent {
        label "docker-agent"
    }
    stages {
        stage {
            steps {
                sh 'sudo docker-compose up -d'
            }
        }
    }
}