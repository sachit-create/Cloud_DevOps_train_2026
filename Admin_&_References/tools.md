# Tools And References
Last Updated: March 1, 2026

## Core Toolchain

- `Linux/Bash`
  URL: https://www.gnu.org/software/bash/
  Verify: `bash --version`
- `Git`
  URL: https://git-scm.com/doc
  Verify: `git --version`
- `Python`
  URL: https://www.python.org/
  Verify: `python3 --version`
- `Node.js`
  URL: https://nodejs.org/
  Verify: `node -v`
- `Docker`
  URL: https://www.docker.com/
  Verify: `docker --version`

## Build And CI/CD

- `Maven`
  URL: https://maven.apache.org/
  Verify: `mvn -v`
- `Gradle`
  URL: https://gradle.org/
  Verify: `gradle -v`
- `Jenkins`
  URL: https://www.jenkins.io/
  Verify: Open Jenkins dashboard and check pipeline status.
- `GitHub Actions`
  URL: https://docs.github.com/actions
  Verify: Open repository `Actions` tab and confirm workflow run status.

## Cloud And IaC

- `AWS Console`
  URL: https://aws.amazon.com/console/
  Verify: `aws --version`
- `Kubernetes`
  URL: https://kubernetes.io/
  Verify: `kubectl version --client`
- `Minikube`
  URL: https://minikube.sigs.k8s.io/docs/
  Verify: `minikube version`
- `Terraform`
  URL: https://developer.hashicorp.com/terraform
  Verify: `terraform -version`

## Training Quick Links

- Notes root: `Daily_Notes/`
- Projects root: `Projects/`
- CI/CD docs: `CI_CD/`
- Work log: `Admin_&_References/Work_Log.md`
- Roadmap: `ROADMAP.md`

## Common Errors And Fixes

- `docker: Cannot connect to the Docker daemon`
  Fix: Start Docker service, then run `docker ps`.
- `mvn: command not found`
  Fix: Install Maven and add it to `PATH`, then verify with `mvn -v`.
- `aws: command not found`
  Fix: Install AWS CLI and verify with `aws --version`.
- `kubectl: command not found`
  Fix: Install kubectl and verify with `kubectl version --client`.
- `terraform: command not found`
  Fix: Install Terraform and verify with `terraform -version`.
- `Permission denied (publickey)` in SSH/Git operations
  Fix: Add correct SSH key and verify with `ssh -T git@github.com`.
