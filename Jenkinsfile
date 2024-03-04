pipeline{
    agent any
    stages {
        stage ("build iamge") {
            steps {
                sh 'docker-compose build'
            }
        }
        stage ("run"){
            steps{
                sh 'docker-compose up'
            }
        }
        // stage ("testing") {
        //     steps {
        //         sh 'docker info'
        //     }
        // }
    }
}