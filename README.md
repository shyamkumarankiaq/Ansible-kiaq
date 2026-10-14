This repository contains the Ansible playbooks I created for my KIAQ Ansible Automation Lab assessment. I used Ansible to install and configure different DevOps tools on an Ubuntu EC2 instance in AWS.

Project Files

ansible.cfg – Ansible configuration file.

inventory.ini – Contains the EC2 server IP address and SSH connection details.

playbooks/ – Contains all the YAML files used for the assessment tasks.

screenshots/ – Contains screenshots of the playbook execution and application pages.

README.md – Project details and instructions.

Playbooks

The playbooks folder contains the following YAML files:

docker.yml – Installs Docker and Docker Compose.

nginx.yml – Installs and configures Nginx.

jenkins.yml – Installs Jenkins.

harbor.yml – Installs the packages required for Harbor.

vault.yml – Installs HashiCorp Vault.

sonarqube.yml – Deploys SonarQube using Docker.

monitoring.yml – Sets up Prometheus and Grafana using Docker Compose.

