# Simple Web Application with Ansible and GitHub Actions

## Introduction
This repository contains a minimal web application architecture that we will use to learn how to integrate Ansible with GitHub Actions. The application is built using Apache and PHP running on a Linux server.

## Repository Structure


ansible/

├── playbook.yml    # The main Ansible playbook for setting up the server

├── inventory       # The Ansible inventory file with the list of servers

└── files/          # Directory containing the application files to be deployed
    
    └── index.php         # Application files (e.g., "Hello World" PHP script)

In this structure:
**ansible**/ is the root directory containing all Ansible-related files.

**playbook.yml** is the playbook file that defines the tasks to be performed by Ansible.

**inventory** is the file that lists the servers where the Ansible playbook will run.

**files/** is the directory where the actual application files are stored, which in this case would be the "Hello World" PHP script and any other necessary files for the web application.

## The Application
The application is a basic "Hello World" PHP file, which is enough for our demonstration purposes.

## Next Steps
Follow the course instructions to upload the source code to your GitHub repository and proceed with the Ansible and GitHub Actions integration.
