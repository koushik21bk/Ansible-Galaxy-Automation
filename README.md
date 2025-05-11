# Ansible-Galaxy-Automation
Ec2/MySql Automation Using Ansible Galaxy


# Ansible Galaxy Automation

This project automates the deployment of AWS EC2 instances and the installation of MySQL using **Ansible Galaxy** roles. It follows the Infrastructure as Code (IaC) approach for efficient and repeatable infrastructure setup in the cloud.

## 🔧 Technologies Used

- **Ansible**
- **AWS EC2**
- **MySQL**
- **Ansible Galaxy Roles**
- **Git / GitHub**
- **Ubuntu (WSL on Windows)**

## 🚀 Features

- Automated EC2 instance provisioning in a specified region.
- MySQL installation and service configuration using Galaxy roles.
- Role-based modular design (separate playbooks for EC2 and MySQL).
- Secure configuration using key pairs and security groups.
- Custom variables for flexible deployment.

## 📁 Project Structure
.
├── ec2_mysql_ansible/
│ ├── ec2.yml # Playbook to launch EC2 instances
│ ├── mysql.yml # Playbook to install MySQL
│ └── roles/ # Galaxy roles
│ └── geerlingguy.mysql/
├── awscliv2.zip # AWS CLI setup 
└── README.md
