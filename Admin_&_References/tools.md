## Tools And References
Last Updated: February 24, 2026

### Build And Framework
- `Spring.io` - Java framework ecosystem and project bootstrap.
  URL: https://spring.io/
  Verify: `java -version`
- `Apache Maven` - Build tool and dependency management.
  URL: https://maven.apache.org/
  Verify: `mvn -v`
- `Gradle` - Build automation tool (alternative to Maven).
  URL: https://gradle.org/
  Verify: `gradle -v`
- `Node.js` - JavaScript runtime for backend and tooling.
  URL: https://nodejs.org/
  Verify: `node -v`
- `Python` - Runtime used for scripting and app development.
  URL: https://www.python.org/
  Verify: `python3 --version`

### Version Control And CI
- `GitLab` - Source hosting, CI/CD pipelines, merge requests.
  URL: https://gitlab.com/
  Verify: `git --version`
- `GitHub` - Source hosting, collaboration, actions.
  URL: https://github.com/
  Verify: `git --version`
- `Jenkins` - CI/CD automation server for build and deployment pipelines.
  URL: https://www.jenkins.io/
  Verify: Open Jenkins UI and check build status.
- `GitHub Actions` - CI/CD workflows integrated with GitHub repositories.
  URL: https://docs.github.com/actions
  Verify: Open repo `Actions` tab and confirm workflow runs.

### Cloud And Networking
- `AWS` - Cloud services (EC2, S3, IAM, RDS, etc.).
  URL: https://aws.amazon.com/console/
  Verify: `aws --version`
- `DNS Propagation Checker` - Validate DNS record updates globally.
  URL: https://www.whatsmydns.net/
  Verify: Open URL and check A/CNAME records.

### DevOps And Infra
- `Docker` - Containerization for build and runtime consistency.
  URL: https://www.docker.com/
  Verify: `docker --version`
- `Docker Hub` - Container image registry.
  URL: https://hub.docker.com/
  Verify: `docker login`
- `Kubernetes` - Container orchestration platform.
  URL: https://kubernetes.io/
  Verify: `kubectl version --client`
- `Terraform` - Infrastructure as Code provisioning tool.
  URL: https://developer.hashicorp.com/terraform
  Verify: `terraform -version`
- `MobaXterm` - Terminal and remote access client.
  URL: https://mobaxterm.mobatek.net/
  Verify: Launch app and test SSH connection.

### Training Workflow Utilities
- `Markdown` - Primary format for day-wise notes and summaries.
  URL: https://www.markdownguide.org/
  Verify: Open `Daily_Notes/*/notes.md` or `work.md` files and confirm readable structure.
- `Jenkinsfile (Pipeline Syntax)` - CI/CD pipeline-as-code for Jenkins practice days.
  URL: https://www.jenkins.io/doc/book/pipeline/syntax/
  Verify: Open local `Jenkinsfile` and confirm stage structure (Checkout/Build/Test/Deploy).
- `Git` - Day-wise progress commits and branch-based practice tracking.
  URL: https://git-scm.com/doc
  Verify: `git --version`

### Quick Access Accounts
- `GitHub`: https://github.com/
- `GitLab`: https://gitlab.com/
- `AWS Console`: https://aws.amazon.com/console/
- `Docker Hub`: https://hub.docker.com/
- `Jenkins`: http://localhost:8080/ (or your server URL)

### Common Errors
- `docker: Cannot connect to the Docker daemon`
  Fix: Start Docker service, then run `docker ps`.
- `mvn: command not found`
  Fix: Install Maven and add it to `PATH`, then run `mvn -v`.
- `aws: command not found`
  Fix: Install AWS CLI and verify with `aws --version`.
- `kubectl: command not found`
  Fix: Install kubectl and verify with `kubectl version --client`.
- `terraform: command not found`
  Fix: Install Terraform and confirm with `terraform -version`.
- `Permission denied (publickey)` during SSH
  Fix: Add correct SSH key and verify with `ssh -T git@github.com`.
