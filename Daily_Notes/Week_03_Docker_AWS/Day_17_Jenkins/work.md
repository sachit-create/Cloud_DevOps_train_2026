# Day 17 - Jenkins (CI/CD) Notes

## What Jenkins Is
Jenkins is an automation server used to implement **CI/CD**:
- **CI (Continuous Integration):** automatically build and test code whenever changes are pushed.
- **CD (Continuous Delivery/Deployment):** automatically prepare or release builds to environments.

Jenkins helps teams reduce manual work, catch issues early, and keep delivery consistent.

## Why We Use Jenkins in DevOps
- Automates repetitive tasks (build, test, deploy).
- Gives fast feedback after each code change.
- Integrates with GitHub/GitLab/Bitbucket and many tools/plugins.
- Maintains pipeline history and logs for troubleshooting.

## Core Jenkins Concepts
- **Node:** machine that runs Jenkins jobs (controller/agent).
- **Job:** a configured task (freestyle or pipeline).
- **Pipeline:** code-defined workflow (`Jenkinsfile`) containing stages.
- **Stage:** logical unit like Build, Test, Deploy.
- **Step:** command inside a stage (`sh`, `echo`, `git`, etc.).

## Typical Jenkins CI/CD Flow
1. Developer pushes code to Git repository.
2. Jenkins webhook/polling triggers the pipeline.
3. Jenkins checks out source code.
4. Build stage compiles/packages the app.
5. Test stage runs unit/integration tests.
6. If successful, artifact is stored and deployed.
7. Team gets status via console output/notifications.

## Example Jenkinsfile (Declarative Pipeline)
```groovy
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/example/repo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building application..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
            }
        }
    }
}
```

## Jenkins + Docker (Relevant to This Week)
- Jenkins can run Docker commands in pipeline steps.
- Useful for creating consistent build environments.
- Example usage:
  - Build image: `docker build -t myapp:latest .`
  - Run tests in container.
  - Push image to Docker Hub/ECR after successful tests.

This connects CI/CD directly with container-based deployments.

## Best Practices
- Store pipeline in source control as `Jenkinsfile`.
- Keep stages small and readable.
- Fail fast: run linting/tests early.
- Use credentials plugin for secrets; never hardcode passwords/tokens.
- Add post actions for notifications and cleanup.
- Restrict plugin usage to trusted/required ones.

## Key Learning Outcome (Day 17)
Today’s focus is understanding how Jenkins automates end-to-end software delivery:
from commit -> build -> test -> deploy, with visibility and repeatability.  
This is a foundational DevOps skill for reliable release management.
