pipeline{
    agent any
    stages {
        // stage ("build docker container") {
        //     steps {
        //         sh 'docker-compose up -d'
        //     }
        // }
        stage ("testing") {
            steps {
                sh 'systemctl start docker'
                sh 'docker info'
            }
        }
    }
}