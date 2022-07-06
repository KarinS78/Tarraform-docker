#Terraform-docker

website:
https://learn.hashicorp.com/collections/terraform/docker-get-started

task 1 - Build Infrastructure - Terraform Docker:
added a file name "main.tf" 
list of command: 
    terraform init
    terraform fmt
    terraform validate
    terraform apply
    terraform show
    terraform state list


task 2 - Change Infrastructure:
change port in line 24
before:
    external = 8000
after: 
    external = 8080


task 3 - Define Input Variables:
Set the container name with a variable
added a new file "variables.tf"
changed in line 21 in main.tf
before:
    name  = "tutorial"
after:
    name  = var.ExampleKarinsoopp

