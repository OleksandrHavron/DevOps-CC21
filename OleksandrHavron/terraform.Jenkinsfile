pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage('Terraform init/plan'){
            steps{
                sh 'pwd'
                sh 'ls -la'
                dir('./tf_files') {
                    sh 'pwd'
                    sh 'ls -la'
                    sh 'terraform init'
                    sh 'terraform plan'
                }
            }
        }
        
    }
}