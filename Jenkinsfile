pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git 'https://github.com/seckmohamed1/projet-pipeline.git'
            }
        }
        stage('build'){
            steps{
                sh 'docker-compose up --build --force-recreate'
            }
        }
        
    }
}
