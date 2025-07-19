pipeline{
    agent any

    stages{
        stage('Cloning Github repo to Jenkins'){
            steps{
                scripts{
                    echo 'Cloning Github repo to Jenskins..............'
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-token', url: 'https://github.com/ghanshyam20/MLOPS-1.git']])
                    }
            }
        }
    }
}

