pipeline {
   agent any

   stages {
      stage('Terraform init') {
         steps {
            
            echo 'hello, maven'
            sh 'terraform init'
            echo 'hi'
             
         }
      }
      stage('Terraform plan') {
         steps {
            sh "terraform plan --var-file=/home/centos/azpoc/first/terraform.tfvars"
            
         }
      }
   }
}
