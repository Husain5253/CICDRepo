pipeline{
    agent any
    stages{
        stage('Checkout external proj') {
            steps {
                git branch: 'master',
                    credentialsId: 'b271cfaf-6789-4c9e-a00a-e7ccab300d39',
                    url: 'git@github.com:fmerchant31/CICDRepo.git'
                sh "ls -lh"
            }
        }
    }
}
