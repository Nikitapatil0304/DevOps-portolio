🚀 DevOps Portfolio – Automated Deployment using GitHub Actions & AWS
This repository contains my personal DevOps Portfolio Website deployed automatically on AWS using GitHub Actions CI/CD pipeline.
📂 Project Structure
Copy code

DevOps-portfolio/
│── index.html
│── style.css
│── .github/
│    └── workflows/
│         └── deploy.yml
│── README.md
index.html – Main website file
style.css – Styling for portfolio
deploy.yml – CI/CD workflow configuration
⚙️ How Deployment Works
Code is pushed to the master branch
GitHub Actions workflow is triggered
Secure SSH connection is established to AWS EC2
Latest code is pulled to /var/www/html
Website updates automatically
🛠️ Technologies Used
Git & GitHub
GitHub Actions
AWS EC2 (Ubuntu)
Nginx
SSH Authentication
🔐 Security
Sensitive credentials are stored securely using GitHub Secrets:
AWS_HOST
AWS_USER
SSH_PRIVATE_KEY
No credentials are hardcoded in the repository.
🌐 Live Deployment
After successful CI/CD execution, the website is accessible via:
Copy code

http://<EC2-Public-IP>
🎯 DevOps Concepts Demonstrated
Continuous Integration
Continuous Deployment
Cloud Infrastructure (AWS)
Automation
Secure Secret Management
👨‍💻 Author
Nikita Patil
DevOps & Cloud Enthusiast
