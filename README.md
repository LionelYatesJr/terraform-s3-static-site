# 🌐 Terraform Static Website on AWS S3

This project uses **Terraform** to deploy a public static website on **Amazon S3**.

## 🚀 Features
- Infrastructure as Code (IaC) using Terraform
- Public S3 bucket with website hosting
- Automatic unique bucket name using `random_id`
- Custom `index.html` and `error.html`
- Access logging disabled for simplicity
- Public access via bucket policy (no ACLs)

## 🌍 Live Site
[Click to view](http://my-terraform-static-site-d7c5cee9.s3-website-us-east-1.amazonaws.com)

> Replace the link with your actual S3 website endpoint if it differs.

## 🛠️ Tech Stack
- Terraform
- AWS S3
- GitHub

## 🧰 Files Included
- `main.tf`: Terraform configuration
- `website/index.html`: Main page
- `website/error.html`: Error page
- `README.md`: Project overview

## 📄 License
This project is open-source and free to use.
