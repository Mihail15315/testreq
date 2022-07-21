pipeline{
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
                   echo 'test' 
            }
        }
        stage('deploy'){
            steps{
                echo 'deploy'
            }
        }
    }
}
