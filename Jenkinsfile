pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                sh 'ls'
            }
        }
        stage('test'){
            steps{
                docker{
                    sh 'docker ps'
                }
            }
        }
        stage('deploy'){
            steps{
                echo 'deploy'
            }
        }
    }
}
