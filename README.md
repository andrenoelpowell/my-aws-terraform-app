# my-aws-terraform-app

This project sets up a basic AWS infrastructure using Terraform. 

## Tools
- Terraform
- AWS EC2
- GitHub + CI/CD (planned)

## Goals
- Simple app test
- Practice infrastructure as code
- Track issues and tasks in GitHub Projects
### ✅ Project Task Checklist

- [ ] Set up AWS provider block in Terraform  
- [ ] Define variables for region, instance type, and AMI  
- [ ] Create Terraform resources for a Linux EC2 instance  
- [ ] Create Terraform resources for a Windows EC2 instance  
- [ ] Add SSH key pair configuration for access  
- [ ] Write outputs for instance public IPs  
- [ ] Create a security group with ports open for SSH, WinRM, and Beats traffic  
- [ ] Write user_data scripts to auto-install Filebeat on Linux  
- [ ] Manually install Filebeat on Windows EC2 instance  
- [ ] Configure Filebeat to forward logs to Logstash/Elastic  
- [ ] Deploy Elasticsearch and Kibana (Elastic Stack) in AWS  
- [ ] Verify Beats communication with Elasticsearch  
- [ ] Create Kibana dashboard for system logs and metrics  
- [ ] Write basic Ansible playbook to install Beats on EC2 instances  
- [ ] Refactor Terraform code using modules  
- [ ] Set up GitLab CI/CD pipeline to deploy Terraform code  
- [ ] Secure AWS credentials using environment variables or GitHub secrets  
- [ ] Implement Terraform remote backend (e.g., S3 + DynamoDB)  
- [ ] Document architecture in the README with a diagram  
- [ ] Create issues for known limitations or TODOs  
