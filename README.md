# AWS Infrastructure Automation with Ansible

## 📖 Description
This project demonstrates the use of **Ansible** to automate the deployment of web infrastructure on **AWS EC2** instances. Using a WSL (Windows Subsystem for Linux) control node, I managed multiple slave servers to install Apache and deploy custom web content.

## 🛠️ Technology Stack
* **Control Node:** WSL (Ubuntu)
* **Cloud Provider:** AWS (EC2)
* **Automation Tool:** Ansible
* **Web Server:** Apache2

## 🚀 Key Features
* **Key Conversion:** Successfully converted `.ppk` keys to OpenSSH `.pem` format for Linux compatibility.
* **Automated Configuration:** Used YAML playbooks to handle system updates, package installation, and service management.
* **Idempotent Deployment:** Designed playbooks that safely check system state before making changes.

## 📁 Project Structure
* `test.yml`: The main playbook for Apache installation.
* `inventory.ini`: Contains server IPs and SSH configurations.
* `ansible.cfg`: Custom configuration to handle host key checking.
