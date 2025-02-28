# CI/CD Pipeline & DevOps Automation with AWS

![CI-CD Pipeline Success.png](CI-CD Pipeline Success.png)

## Overview
This project is part of a 7-part DevOps series, where I implemented a fully automated CI/CD pipeline for an AWS-based web application. The pipeline integrates AWS CodePipeline, CodeBuild, CodeDeploy, and CodeArtifact, enabling seamless software deployment and automation.

## Goal
Automate software release processes to streamline deployments, reduce errors, and ensure reliability.

<br>

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup and Deployment](#setup-and-deployment)
- [Challenges Faced](#challenges-faced)
- [Key Learnings](#key-learnings)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

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

## Setup and Deployment
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
⚠️ Frequent EC2 connection timeouts → Resolved by restarting VSCode and rebooting the instance.<br>
⚠️ Git authentication issue → Explored credential storage with git config --global credential.helper store.<br>
⚠️ CodeArtifact Setup Delays → Adjusted the pipeline to handle dependency storage efficiently.

<br>

## Key Learnings
✔️ Built a full CI/CD pipeline from scratch using AWS services.<br>
✔️ Mastered GitHub integration with AWS CodePipeline.<br>
✔️ Implemented automated deployments and rollback strategies with CodeDeploy.<br>
✔️ Used CloudFormation to provision infrastructure automatically.

<br>

## Future Enhancements
📌 Add monitoring & logging with AWS CloudWatch.<br>
📌 Implement IAM security best practices for pipeline access control.<br>
📌 Extend the pipeline to support multi-environment deployments (Dev → Staging → Prod).

<br>

## Contact

*   Email: joeyacostax@gmail.com

*   [LinkedIn](https://www.linkedin.com/in/joeyacosta/)
    
*   [Portfolio & Other AWS Projects](https://learn.nextwork.org/portfolio)
