# CI/CD Pipeline & DevOps Automation with AWS

## Overview
This project is part of a 7-part DevOps series, where I implemented a fully automated CI/CD pipeline for an AWS-based web application. The pipeline integrates AWS CodePipeline, CodeBuild, CodeDeploy, and CodeArtifact, enabling seamless software deployment and automation.

## Goal
Automate software release processes to streamline deployments, reduce errors, and ensure reliability.

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Project Overview
This project showcases end-to-end CI/CD automation using AWS services.
- Source Control: GitHub integration for version control.
- Build Automation: AWS CodeBuild for compiling and packaging.
- Artifact Management: AWS CodeArtifact for dependency storage.
- Deployment Automation: AWS CodeDeploy for zero-downtime rollouts.
- Infrastructure as Code (IaC): AWS CloudFormation for provisioning cloud resources.

🔹 Impact: This pipeline ensures automated, consistent, and error-free deployments of a Java-based web app.

<br>

## Technologies Used

- Version Control: Git, GitHub
- CI/CD Automation: AWS CodePipeline, CodeBuild, CodeDeploy, CodeArtifact
- Infrastructure as Code (IaC): AWS CloudFormation
- Development: VSCode, AWS EC2 (for development environment)
- Automation & Scripting: AWS CLI

<br>

## Setup & Deployment
To set up this project on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/joeycloudio/nextwork-devops-webapp.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-devops-webapp
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```
4. Deploy using AWS CodePipeline:
- Connect GitHub to AWS CodePipeline.
- Define build and deployment stages using AWS services.

<br>

## Challenges Faced
- Frequent EC2 connection timeouts → Resolved by restarting VSCode and rebooting the instance.
- Git authentication issue → Explored credential storage with git config --global credential.helper store.
- CodeArtifact Setup Delays → Adjusted the pipeline to handle dependency storage efficiently.

## Key Learnings
- Built a full CI/CD pipeline from scratch using AWS services.
- Mastered GitHub integration with AWS CodePipeline.
- Implemented automated deployments and rollback strategies with CodeDeploy.
- Used CloudFormation to provision infrastructure automatically.

## Future Enhancements
- Add monitoring & logging with AWS CloudWatch.
- Implement IAM security best practices for pipeline access control.
- Extend the pipeline to support multi-environment deployments (Dev → Staging → Prod).

## Contact
Email: [joeyacostax@gmail.com](mailto:joeyacostax@gmail.com)
Linkedin: [LinkedIn](www.linkedin.com/in/joeyacosta)
