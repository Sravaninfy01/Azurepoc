pipeline {
   agent any

   stages {
      stage('Terraform plan') {
         steps {
            terraform plan --var-file=/home/centos/azpoc/first/terraform.tfvars
         }
      }
   }
}
