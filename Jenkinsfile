pipeline {
   agent any

   stages {
      stage('Terraform plan') {
         steps {
            sh "terraform plan --var-file=/home/centos/azpoc/first/terraform.tfvars"
         }
      }
   }
}
