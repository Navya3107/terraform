pipeline{
    agent any
    
        tools{
            terraform 'terraform'
        }
        stages{
            stage('cloning'){
                steps{
                    git 'https://github.com/Navya3107/terraform.git'
                    
                }
             }
            stage('terraform init'){
                steps{
                    sh 'terraform init'
                }
                
             }
             stage('terraform plan'){
                steps{
                    sh 'terraform plan'
                }
                
             }
             stage('terraform apply'){
                steps{
                    sh 'terraform apply --auto-approve'
                }
                
             }
             
         }
    }

    //jenik file
