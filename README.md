# 3-tier-architecture-on-aws-using-terraform
 Following components will be created -

Two private subnets
Private Route table association with subnets
Two security groups
  - Security group for load balancer
  - Security group for APP servers
  - 
Application load balancer - internal
Listener group
Target group
Two auto-scaling groups

 ![image](https://github.com/Abd-al-RahmanH/3-Tier-architecture-code-in-Terraform-/assets/120451942/b94e1e05-bc4f-4c18-aa36-87f6176ce906)
 

 To get this infrastructure
 1.Install Terraform  and AWS cli
 2.Then type these command sin terminal 
   terraform init
   terraform plan
   terraform apply -auto-approve
   then after finishing delete this by terraform destroy.


