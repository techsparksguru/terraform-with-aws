# Terraform with AWs
Learn terraform infrastruction automation on AWS

# Course Contents
- Course Overview
    - Overview
    - Audience
    - Pre-requisites
        - Basic Knowledge of Cloud Computing and AWS, Windows/Linux/Mac
        - AWS Account (Preferred)
- Introduction
    - Understanding provisioning
    - What is Terraform?
    - Why?
- Setup
    - Setup in Mac
    - Setup in Ubuntu
    - Setup in Windows
    - Setup with docker
    - Install awscli
    - Configure git
- Configure
    - Get an AWS Account
    - Create IAM user
    - Obtain ACCESSKEY & SECRETKEY
    - Configure credentials using awscli
- Development Tools
    - Install visual studio code
    - Install terraform plugin
- HelloWorld
    - Understanding syntax
        - HCL
        - JSON
    - Configure Provider
        - What is a Provider?
        - Provider landscape
        - Configure terraform
    - Provision S3 Bucket
    - Development flow
        - init
        - validate
        - plan
        - apply
    - Deleting the provisioned S3 Bucket
        - destroy
- Overview of different components
    - variables
    - resources
    - outputs
    - datasource
    - modules
    - functions
    - expressions
- Project Structure
    - Organizing your code
- StyleGuide
- Understanding Terraform State files
- Managing State files
    - Managing state in local
    - Managing state in remote (s3)
    - Encrypting state
    - Best practices
- Input & Output variables
- Provisioning different resources (independantly)
    - Provisioning S3
    - Provision EC2
    - Provision EIP
- Provisioning different resources (dependant)
- Understanding dependancy graphs
    - terraform graph
    - visualize through graphviz
    - visualize through Blast radius
- Provisioning Applications
    - Deploying a three-tier application
- Understanding templates
- Understanding Modules
    - What?
    - Why?
        - code reuse
        - abstraction
        - share
        - versioned artifacts
    - Creating a module
    - Using a module
    - Extending a module
    - Using external modules
- Creating Modules
    - Structure
    - Syntax
- Extending Modules
- Using External Modules
- Managing multiple environments
    - Using Workspaces
- Locking states
- Managing Secrets
- Running terraform for Automation in CI/CD


