# Introduction to Azure DevOps

Azure DevOps is a platform developed by Microsoft that integrates multiple services to enhance the Software Development Life Cycle (SDLC).

It helps DevOps Engineers automate processes, reduce manual effort, and accelerate feature and bug fix deployment.

## What is SDLC?
SDLC includes phases like planning, design, development, testing, deployment, and maintenance.

Each phase involves collaboration between teams to deliver a feature or product efficiently.
### Role of DevOps in SDLC
DevOps is a culture aimed at automating and optimizing these phases.

DevOps Engineers focus on reducing manual tasks, such as testing and deployment, using automation tools.

Example: Reducing a manual delivery timeline from three months --> day's

## How Azure DevOps Enhances SDLC?
Azure DevOps centralizes SDLC processes, providing solutions for planning, development, testing, and deployment in one platform.

Services include:

Boards: For project planning and management, similar to Jira.

Repos: Version control system for source code, Terraform scripts, Kubernetes manifests, etc.

Pipelines: Automates CI/CD processes to streamline testing and deployment.

Test Plans: Facilitates test case creation, management, and execution.

Artifacts: Stores build outputs, binaries, and other artifacts for reuse.
--------------------------------------------------------------------
Boards:

Helps teams plan and manage work items, backlogs, and sprints.

Supports collaboration among product owners, developers, and QA teams.

Repos:

Provides a repository for version control to manage source code and scripts.

Supports Git and other version control systems.

Pipelines:

Enables Continuous Integration and Continuous Deployment (CI/CD).

Automates the process of testing and deploying code upon committing changes to the repository.

Test Plans:

Allows QA teams to create test cases, plan test scenarios, and execute tests.

Tracks testing progress and integrates with CI/CD pipelines.

Artifacts:

Stores outcomes of CI/CD pipelines, such as binaries, jar files, or other build artifacts.

Facilitates artifact reuse across projects.
------------------------------------------------------------------

### Benefits of Azure DevOps

**Centralized Platform:**

Combines tools like Jira, Jenkins, ArgoCD, and JFrog into one solution.

Simplifies tool maintenance and reduces complexity.

**Automation at Every Stage:**

Automates tasks like testing, deployment, and artifact storage.

Enhances collaboration and reduces delivery timelines.

### Example Workflow SDLC

Planning:

Use Boards to define and manage tasks, sprints, and backlog items.

Development:

Developers commit code to Repos, maintaining a version history.

CI/CD Pipelines:

Pipelines trigger automated builds, tests, and deployments when changes are pushed to Repos.

Testing:

QA teams create test plans in Test Plans and integrate them into the CI/CD pipeline for automated testing.

Deployment:

Pipelines handle automated deployments to production or staging environments.

Artifact Management:

Store build outputs or other relevant files in Artifacts for later use.

