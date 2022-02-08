pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage('Terraform init/plan'){
            steps{
                sh 'pwd'
                dir('./tf_files') {
                    sh 'pwd'
                    sh 'terraform init'
                    sh 'terraform plan'
                }
            }
        }
        
    }
}