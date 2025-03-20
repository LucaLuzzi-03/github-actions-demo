# GitHub Actions Glossary

## CI (Continuous Integration)
Every commit and change done by each member of a team within a repository. It ensures that changes are tested and integrated into the main codebase frequently.

## CD (Continuous Delivery / Continuous Deployment)
CD refers to the process where workflows are executed to deliver changes efficiently. The key difference between Continuous Delivery and Continuous Deployment is:
- **Continuous Delivery**: Executes all processes, and when everything is green (successful), a final manual step is required for deployment.
- **Continuous Deployment**: When everything is green, the deployment happens automatically without manual intervention.

## Workflow
A workflow is defined within a `.yaml` file in a GitHub Actions repository. It consists of:
- **Triggers**: Define what starts a workflow.
- **Jobs**: Groups of steps that run sequentially or in parallel.
- **Steps**: Individual tasks executed within a job.
- **Runners**: Virtual machines (VMs) that execute the jobs.

## Triggers
Triggers define what initiates a workflow execution. Common triggers include:
- Push events (e.g., `push` to `main` branch)
- Pull requests
- Scheduled workflows
- Manual workflows (via GitHub UI or API)

## Jobs
Jobs consist of a series of steps executed within a workflow. By default, jobs run in parallel unless configured otherwise.

## Steps
A step is an individual task within a job. It can execute commands, scripts, or GitHub Actions.

## Runners
Runners are virtual machines that execute the jobs in a workflow. GitHub provides hosted runners, but you can also configure self-hosted runners for more control.

---
This document provides a foundational understanding of GitHub Actions concepts and terminology to help you efficiently manage workflows and CI/CD processes.

