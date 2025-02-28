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

- **Troubleshooting Tip**: My connection timed out frequently, so I rebooted my EC2 instance and restarted VSCode more times than I’d like. This usually solved the issue, so I didn't investigate further (though an IP address change on my WiFi could have been the cause, it didn't seem to be). In fact, my connection dropped while writing this README at this exact point!

<br>

## Contact
If you have any questions or comments about the NextWork Web Project, please contact:
Joey - [joeyacostax@gmail.com](mailto:joeyacostax@gmail.com)

[LinkedIn](www.linkedin.com/in/joeyacosta)

<br>

## Conclusion
Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects.

A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project guide and support. [You can get started with this DevOps series project too by clicking here.](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)

