# task11
Main:
Create free tier aws account
Install terraform https://www.terraform.io/ 
Using terraform spin up infrastructure. Terraform configuration should be:
- LC (launch configuration) with ami
- ASG (autoscaling group) with healthcheck type ELB
- ALB (application load balancer) with target group
- SG (security groups), access to the application should be only from ALB
Output from task: Commit terraform configuration into task11 branch and send link by email to your github repo
