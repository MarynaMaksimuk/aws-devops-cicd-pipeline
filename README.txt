End-to-End DevOps Project: 6-Day Challenge

Hands-on Cloud Engineering | AWS | CI/CD | Automation | DevOps

Overview

This repository documents my journey through the NextWork 6-Day DevOps Challenge, where I build and automate an end-to-end application delivery workflow using AWS services and DevOps practices.

The project focuses on taking a Java web application from development and source control through dependency management, automated builds, and application deployment. Each day builds on the previous day's work, demonstrating how individual AWS services can be integrated into a repeatable software delivery process.

My goal is to strengthen my practical DevOps engineering skills, deepen my understanding of cloud infrastructure and CI/CD automation, and apply these concepts to real-world deployment workflows.

Project Objectives
Set up a cloud-based development environment.
Integrate GitHub for source control and version management.
Manage Java application dependencies using AWS CodeArtifact.
Automate application builds and validation using AWS CodeBuild.
Deploy the application using AWS CodeDeploy.
Integrate the delivery workflow using AWS CI/CD services.
Document implementation steps, troubleshooting, and lessons learned.
Technology Stack
Technology		Purpose
Amazon EC2		Cloud-based development and application hosting
Git and GitHub		Source control and code versioning
Java and Maven		Application development, dependency management, and builds
AWS CodeArtifact	Package and dependency management
AWS CodeBuild		Automated builds and validation
Amazon S3		Storage for application artifacts
AWS CodeDeploy		Application deployment automation
AWS CodePipeline	CI/CD workflow orchestration
Linux and Bash		Command-line operations and automation
AWS IAM			Identity and access management
VS Code Remote SSH	Remote development on EC2



Daily Challenge Roadmap
Day 1 — Cloud Development Environment

Folder: day-01-web-app-setup

Set up an Amazon EC2 development environment.
Connect to the instance using SSH and VS Code Remote SSH.
Install and configure Java and Maven.
Prepare the Java web application for development.
Day 2 — GitHub Integration

Folder: day-02-github-integration

Initialize and configure Git.
Connect the project to a GitHub repository.
Commit and push application changes.
Establish source control as the foundation of the CI/CD workflow.
Day 3 — Dependency Management with AWS CodeArtifact

Folder: day-03-codeartifact

Configure an AWS CodeArtifact domain and repository.
Integrate Maven with CodeArtifact.
Publish and manage application packages.
Explore repository permissions and dependency access.
Day 4 — Continuous Integration with AWS CodeBuild

Folder: day-04-codebuild-ci

Configure an AWS CodeBuild project.
Define build instructions in buildspec.yml.
Automate application compilation and validation.
Integrate the source repository with the build process.
Day 5 — Application Deployment with AWS CodeDeploy

Folder: day-05-codedeploy

Prepare the application deployment bundle.
Configure deployment instructions and lifecycle hooks.
Deploy the application to an EC2 environment.
Validate deployment results and troubleshoot issues.
Day 6 — End-to-End CI/CD with AWS CodePipeline

Folder: day-06-codepipeline-cicd

Connect source, build, and deployment stages.
Automate the application delivery workflow.
Validate the end-to-end pipeline.
Document deployment results and potential improvements.




Key Learning Areas

Throughout this project, I am developing practical experience with:

CI/CD automation: Connecting source control, builds, and deployment into a repeatable workflow.
Cloud engineering: Configuring and working with AWS infrastructure and services.
Build and dependency management: Using Maven and CodeArtifact to manage Java application builds and packages.
Deployment automation: Managing application deployment workflows and validating releases.
Linux and scripting: Working with Linux environments, command-line tools, and automation scripts.
Troubleshooting: Investigating configuration issues, permissions, build failures, and deployment problems.
Documentation: Recording implementation steps, technical decisions, and lessons learned.


An important part of this project is learning to investigate and resolve real configuration issues rather than simply following deployment instructions.

This section will capture issues encountered during implementation, their root causes, the steps taken to resolve them, and the lessons learned.

Examples of areas to document include:

SSH connectivity and remote development configuration.
Git authentication and repository synchronization.
AWS IAM permissions and CodeArtifact access.
Maven build and dependency resolution failures.
CodeBuild configuration and deployment errors.

Only confirmed issues and solutions will be added as the project progresses.

Future Improvements

After completing the core challenge, potential improvements include:

Provisioning infrastructure using Terraform.
Automating server configuration with Ansible.
Adding automated integration and smoke tests.
Implementing environment-specific deployments for Dev, QA, and Production.
Introducing deployment approvals, health checks, and rollback safeguards.
Exploring equivalent CI/CD workflows using Azure DevOps.




About

This project is part of my ongoing professional development in DevOps and cloud engineering. It demonstrates my commitment to hands-on learning, automation, continuous improvement, and building reliable software delivery workflows.

Areas of interest: DevOps Engineering | Cloud Infrastructure | CI/CD | Infrastructure as Code | Automation | Platform Engineering