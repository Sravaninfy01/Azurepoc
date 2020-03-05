node {
    
    stage('Clone sources') {
        git url: 'https://github.com/Sravaninfy01/Azurepoc.git'
    }

    stage('Create Resource') {
        // Tool name from Jenkins configuration
        terraform plan --var-file=/home/centos/azpoc/first/terraform.tfvars
        // terraform apply --var-file=/home/centos/azpoc/first/terraform.tfvars -auto-approve
    }
