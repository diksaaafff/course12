# CI/CD Final Project - Coursera

This project demonstrates the implementation of a complete CI/CD pipeline using GitHub Actions, Tekton, and OpenShift.

## Project Details
- **Name:** CI/CD Pipeline Implementation
- **Description:** A simple Flask application with automated linting, testing, and deployment configurations.
- **Technologies Used:**
  - Python / Flask
  - GitHub Actions (CI)
  - Tekton (Pipelines)
  - OpenShift (Deployment)

## Features
- Automated Linting with `flake8`
- Automated Unit Testing with `nose`
- CI Pipeline via GitHub Actions
- Cloud-native CI/CD via Tekton
- Deployment configurations for OpenShift

## Submission Instructions

To answer the questions in the final project:

1.  **Question 1 (README.md):** Submit the link to this `README.md` file in your repository.
2.  **Question 2 (GitHub Workflow):** Submit the link to `.github/workflows/workflow.yml`. It contains both `flake8` linting and `nosetests` unit testing.
3.  **Question 3 (Tekton Tasks):** Submit the link to `.tekton/tasks.yml`. It contains both the `cleanup` task and the `nose-tests` task.
4.  **Question 4 (PVC Details):** Use the OpenShift console to take a screenshot of your `PersistentVolumeClaim` (PVC) details. Save it as `oc-pipelines-console-pvc-details.png` and upload it to the `screenshots/` folder.
5.  **Question 5 (GitHub Actions Output):** Copy the console output from a successful GitHub Actions run and paste it into `logs/github_actions_output.txt`.
6.  **Question 6 (OpenShift Pipeline Details):** Take a screenshot of the `oc-pipelines-oc-final` pipeline in the OpenShift console. Save it as `oc-pipelines-oc-final.png` in the `screenshots/` folder.
7.  **Question 7 (OpenShift Pipeline Success):** Take a screenshot of the successful "green" pipeline run. Save it as `oc-pipelines-oc-green.png` in the `screenshots/` folder.
8.  **Question 8 (OpenShift App Log):** Use `oc logs <pod_name>` to get the logs of your running application and paste them into `logs/openshift_app_log.txt`.
