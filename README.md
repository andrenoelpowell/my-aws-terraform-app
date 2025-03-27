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
# ✅ Project Setup Task List: AWS + VSCode + GitHub + Terraform + Flask

## 🔧 Initial Setup
- [ ] Create a GitHub repository named `my-aws-terraform-app`
- [ ] Clone the repo locally using VSCode terminal
- [ ] Create project folder structure: `terraform/`, `app/`

## 🐍 Flask App
- [ ] Create `app/app.py` with a basic Flask “Hello” route
- [ ] Create `app/requirements.txt` and add `flask`
- [ ] Test the app locally (optional)

## 🧱 Terraform Infrastructure
- [ ] Write `terraform/main.tf` with AWS provider
- [ ] Create `aws_key_pair` resource
- [ ] Create `aws_security_group` allowing ports 22 and 5000
- [ ] Create `aws_instance` with `user_data` script
- [ ] Write `terraform/setup.sh` to install Flask and run the app
- [ ] Make `setup.sh` executable

## 🚀 Terraform Deploy
- [ ] Run `terraform init`
- [ ] Run `terraform apply`
- [ ] Confirm EC2 instance launches successfully

## 🌍 App Verification
- [ ] Note the public IP of the EC2 instance
- [ ] Visit `http://<EC2-IP>:5000` and confirm the Flask app responds

## 🔄 Version Control
- [ ] Commit changes with message: `Initial Terraform + Flask setup`
- [ ] Push code to GitHub

## 🧠 Optional Next Steps
- [ ] Add Terraform output for public IP
- [ ] Add remote state storage (S3 + DynamoDB)
- [ ] Add GitHub Actions for Terraform validation and deployment
- [ ] Automate Flask app deployment with CI/CD
- [ ] Secure traffic with HTTPS using ACM and ALB

