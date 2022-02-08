pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage('Terraform init/plan'){
            steps{
                sh 'terraform init'
                sh 'terraform plan'
            }
        }
        
    }
}