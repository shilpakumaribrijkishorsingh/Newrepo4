GCP CI Pipeline Setup using CircleCI



Overview

This document explains how to set up a basic Continuous Integration (CI) pipeline on Google Cloud Platform using CircleCI.



Step 1: Connect CircleCI to GitHub

\- Sign in to CircleCI

\- Connect your GitHub repository

\- Authorize CircleCI access



Step 2: Configure CircleCI Pipeline

\- Create a `.circleci/config.yml` file

\- Define pipeline jobs and workflows



Pipeline Stages



Build Stage

\- Install dependencies

\- Build the application or prepare the Python script



Test Stage

\- Run automated tests to validate functionality



Deploy Stage

\- Deploy the application to a Google Compute Engine VM

\- Verify deployment success



Build Triggers

\- Configure CircleCI to automatically trigger pipelines on every GitHub commit

