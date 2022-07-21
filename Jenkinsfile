pipeline{
    agent any
    stages{
        stage('build'){
            agent{
            docker {
          image 'node:16-alpine'
        }
            }
        }
        stage('test'){
            steps{
                    sh 'docker ps'
            }
        }
        stage('deploy'){
            steps{
                echo 'deploy'
            }
        }
    }
}
