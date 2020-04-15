# Flux7 Trial Project

# Introduction
   This project is to create a PHP installed EC2 instance with an ansible playbook with a landing  page saying "Welcome to Flux7!

# Setup

# You will need the following:

    Install Python 3.6.9
    Install ansible 2.8.6
    Install the AWS CLI  
    A repository link

# Pre-requisites:
    
    An AWS account. aws configure with an account with programmatic access. 
    You need to replace KeyName: roopakeypair for ansible-playbook to run successfully
    Unique stack name for cloud formation template


# Deploying the current stack

     Created a cloud formation template that launches an EC2 instance with PHP web server
     Ran playbook ansible-playbook to deploy the stack.


# Running the ansible-playbook

    ansible-playbook -i hosts deploy.yml

# Tasks

    Linux EC2 instance is running on AWS and is publicly accessible.
    Instance is configured with an Ansible playbook.
    The playbook installs a PHP web server and a landing page that says "Welcome to Flux7!"
    The playbook code is stored in a publicly accessible Git repository.
