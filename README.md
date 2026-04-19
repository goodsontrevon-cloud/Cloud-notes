# Cloud-notes
## Cloud Engineering Journey

This repository documents my journey from zero to becoming a cloud engineer.

I am learning the fundamentals of cloud computing, Linux, networking, and AWS, and using this repo to track everything I learn along the way.

---

## Table of Contents
- [What This Repo Includes](#what-this-repo-includes)
- [Why I Made This](#why-i-made-this)
- [Goal](#goal)
- [Progress Tracker](#progress-tracker)
- [Learning Log](#learning-log)
- [Notes](#notes)
- [What I'm Learning](#what-im-learning)
- [Key Concepts](#key-concepts)
- [Terraform AWS Lab](#terraform-aws-lab)

---

## What This Repo Includes
- Beginner-friendly notes written in my own words
- Key cloud concepts (AWS servers, storage, networking)
- Linux command line basics
- Git and GitHub practice
- Step-by-step learning progress

---

## Why I Made This
I created this repo to stay consistent, build a strong foundation, and publicly track my progress as I transition into cloud engineering.

---

## Goal
To build real-world cloud projects and become job-ready for a junior cloud engineer role.

---

## 📊📈 Progress
Currently progressing through my cloud engineering roadmap, building hands-on projects and documenting each step.

---

## Progress Tracker
- [x] Created GitHub account
- [x] Created first repository
- [x] Added first cloud notes
- [x] Learned basic Linux commands
- [x] Learned AWS basics
- [x] Built first cloud project (EC2 instance)
- [x] Learned Infrastructure as Code with Terraform

---

## Learning Log

### 📆 Day 1
Started learning cloud fundamentals and created my first GitHub repository.

### 📆 Day 2
Learned basic Linux commands, created structured notes, and improved repo navigation.

➡️ [View Reflection](day-2-reflection.md)

### 📆 Day 3
Learned Git and GitHub workflow, cloned my repository locally, and used git add, commit, and push to update my project.

➡️ [View Reflection](day-3-reflection.md)

### 📆 Day 4
Created AWS account, set up IAM user for security, and built my first cloud resource using S3 with file upload and versioning.

➡️ [View Reflection](day-4-reflection.md)

### 📆 Day 5 – First Cloud Server (EC2)
- Launched my first EC2 instance (t2.micro) using AWS Free Tier
- Connected to the server using EC2 Instance Connect
- Installed Apache web server (`httpd`)
- Started and enabled the web service
- Accessed my server through a public IP in the browser
- Created a custom webpage using a simple command
- Learned how security groups control inbound traffic (ports 22 & 80)

**Key Takeaways:**  
EC2 is a virtual machine in the cloud that allows me to run real applications and host websites. I now understand how servers are deployed and accessed remotely.

### 📆 Day 6 – Terraform (Infrastructure as Code)
- Installed Terraform and verified setup
- Created a new project (`terraform-aws-lab`)
- Wrote my first Terraform configuration file (`main.tf`)
- Defined an AWS provider and EC2 resource
- Ran `terraform init`, `plan`, and `apply`
- Successfully deployed an EC2 instance using code instead of the AWS console
- Destroyed resources using `terraform destroy` to prevent charges

**Key Takeaways:**  
Terraform allows me to automate infrastructure using code. Instead of manually creating resources, I can define and manage everything programmatically, which is how real cloud environments are built.

---

## Notes
- [Internet Basics](Internet-basics.md)
- [Linux Basics](Linux-basics.md)
- [AWS Basics](aws-basics.md)
- [Git Basics](git-basics.md)
- [Day 2 Reflection](day-2-reflection.md)
- [Day 3 Reflection](day-3-reflection.md)
- [Day 4 Reflection](day-4-reflection.md)
- [Day 5 Reflection](day-5-reflection.md)
- [Day 6 Reflection](day-6-reflection.md)

---

## What I'm Learning
- Cloud computing fundamentals
- Linux and command line basics
- Networking basics
- AWS core services
- Git and GitHub
- Infrastructure as Code with Terraform

---

## Key Concepts

### What is Cloud Computing?
Cloud computing is using servers, storage, and services over the internet instead of owning physical hardware.

### What is AWS?
AWS (Amazon Web Services) is a cloud provider that offers services like virtual machines, storage, and databases.

### What is GitHub?
GitHub is a platform used to store code, track changes, and share projects.

---

## Terraform AWS Lab

This project uses Terraform to create AWS infrastructure.

### What I Built
- EC2 instance using Terraform
- Infrastructure defined as code

### Files
- `main.tf` → defines resources
- `variables.tf` → stores variables
- `outputs.tf` → displays outputs

### Commands Used
```bash
terraform init
terraform plan
terraform apply
terraform destroy
```