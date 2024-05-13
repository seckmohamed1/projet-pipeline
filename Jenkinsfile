pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                sh '$ docker rm $(docker ps -aq)'
            }
        }
        stage('build'){
            steps{
                sh 'docker-compose up --build --force-recreate'
            }
        }
        
    }
}
