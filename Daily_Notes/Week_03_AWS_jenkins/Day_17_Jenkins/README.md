# Day 17 - Jenkins Practice Summary

## What I Practiced

- Understood Jenkins role in CI/CD (build, test, deploy automation).
- Reviewed Jenkins core concepts: job, pipeline, stage, step, node.
- Practiced pipeline flow from Git commit to deployment steps.
- Learned how Jenkins integrates with Docker for container-based delivery.

## Key Commands Used

- `git --version`
- `docker --version`
- `docker build -t myapp:latest .`

## Pipeline Skeleton Used

```groovy
pipeline {
    agent any
    stages {
        stage('Checkout') { steps { echo 'Checkout code' } }
        stage('Build')    { steps { echo 'Build app' } }
        stage('Test')     { steps { echo 'Run tests' } }
        stage('Deploy')   { steps { echo 'Deploy app' } }
    }
}
```

## Outcome

- Built strong fundamentals for Jenkins-based CI/CD and prepared for real project pipelines.

## Reference

- Detailed notes: `Daily_Notes/Week_03_AWS_jenkins/Day_17_Jenkins/work.md`
