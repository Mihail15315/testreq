pipeline{
    agent any
    agent{
            docker {
          image 'node:16-alpine'
        }
            }
    stages{
        stage('build'){
            steps{
            sh 'node --version'
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
