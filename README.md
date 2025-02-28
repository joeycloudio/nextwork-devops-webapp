# CI/CD Pipeline & DevOps Automation with AWS

Welcome to this project combining Java web app development and AWS CI/CD tools!

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

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I'm doing this project to complete all 7 of 7 DevOps projects in this NextWork project series and complete the CI/CD Pipeline project at the end.

- CI/CD Pipeline will fill a major skills gap currently for me in my pursuit of a Cloud Engineer role!

<br>

## Technologies
Here’s what I’m using for this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- **VSCode**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **[COMING SOON] AWS CodeArtifact**: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **[COMING SOON] AWS CodeBuild**: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **[COMING SOON] AWS CodeDeploy**: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.
- **[COMING SOON] AWS CodePipeline**: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.

- **Challenges Faced**: My connection timed out frequently, so I rebooted my EC2 instance and restarted VSCode more times than I’d like. This usually solved the issue, so I didn't investigate further (though an IP address change on my WiFi could have been the cause, it didn't seem to be). In fact, my connection dropped while writing this README at this exact point!

- The project mentioned that Git would prompt for a username and password, but I didn’t encounter that issue. My pushes were made as the EC2 user, and I was able to update my username. However, I wanted to log in with my credentials as described in the project. I dug around to check how my credentials were being stored using the git "config --global credential.helper store" command

<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/joeycloudio/nextwork-devops-webapp.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

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

