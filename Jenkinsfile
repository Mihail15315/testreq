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
                docker('docker'){
                    sh 'docker ps -a'
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
