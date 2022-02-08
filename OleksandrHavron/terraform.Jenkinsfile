pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage('Terraform init/plan'){
            steps{
                sh 'terragorm init'
                sh 'terraform plan'
            }
        }
        
    }
}