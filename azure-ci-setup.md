Azure CI Pipeline Setup using Azure DevOps



Overview

This document describes how to set up a basic Continuous Integration (CI) pipeline on Microsoft Azure using Azure DevOps.



Step 1: Create an Azure DevOps Project

\- Sign in to Azure DevOps

\- Create a new project

\- Connect the project to the GitHub repository



Step 2: Configure the CI Pipeline

\- Create a new pipeline in Azure DevOps

\- Select GitHub as the source repository

\- Choose YAML-based pipeline configuration



Pipeline Stages



Build Stage

\- Install required dependencies

\- Build the application or prepare the Python script



Test Stage

\- Run automated unit tests

\- Validate application functionality



Deploy Stage

\- Deploy the application to an Azure Virtual Machine

\- Verify successful deployment



Build Triggers

\- Configure pipeline triggers to run automatically on every code push to the repository

