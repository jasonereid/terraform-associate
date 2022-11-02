# Terraform Associate Study Guide
Study guide for Terraform Associate Certification 002

### The Basics

All Terraform files end in a .tf extension. 

Terraform uses a declarative approach to infrastructure as code (IaC) - you declare what you want to change/destroy/update and Terraform makes it so.



    terraform init - initializes the terraform engine. Run this first.
  
    terraform plan - creates a plan for your main.tf configuration file
  
    terraform validate - validates the current local configuration plan (does not validate any cloud resources, only the config file)
  
    terraform apply - applies the changes defined in your main.tf file
    terraform apply -auto-approve will apply the changes without asking for approval
  
    terraform destroy - removes everything defined in your main.tf
  
    terraform show - shows the details of the State file
  
  
