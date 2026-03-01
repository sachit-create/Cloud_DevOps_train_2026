# Jenkins Notes

## Purpose

Use Jenkins for CI/CD automation with stage-based pipelines for checkout, build, test, and deploy.

## Core Concepts

- `Job`: Configured task in Jenkins
- `Pipeline`: Code-defined workflow (`Jenkinsfile`)
- `Stage`: Logical unit (Checkout, Build, Test, Deploy)
- `Step`: Command execution inside stage (`sh`, `echo`, etc.)
- `Agent`: Execution environment

## Declarative Pipeline Example

```groovy
pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps { echo 'Checking out code' }
    }
    stage('Build') {
      steps { echo 'Building application' }
    }
    stage('Test') {
      steps { echo 'Running tests' }
    }
    stage('Deploy') {
      steps { echo 'Deploying application' }
    }
  }
}
```

## Repository References

- Day 07 sample files:
  - `Daily_Notes/Week_02_Docker_AWS/Day_07_Java_Pushed/Jenkinsfile`
  - `Daily_Notes/Week_02_Docker_AWS/Day_07_Java_Pushed/script.groovy`
- Day 17 summary:
  - `Daily_Notes/Week_03_AWS_jenkins/Day_17_Jenkins/README.md`
- Day 20 revisit summary:
  - `Daily_Notes/Week_04_KBs_IaC/Day_20_jenkins(again)/README.md`

## Typical Validation Commands

- `git --version`
- `docker --version`
- `docker ps`
