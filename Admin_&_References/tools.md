## Tools And References
Last Updated: February 15, 2026

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

### Version Control And CI
- `GitLab` - Source hosting, CI/CD pipelines, merge requests.
  URL: https://gitlab.com/
  Verify: `git --version`
- `GitHub` - Source hosting, collaboration, actions.
  URL: https://github.com/
  Verify: `git --version`

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
- `MobaXterm` - Terminal and remote access client.
  URL: https://mobaxterm.mobatek.net/
  Verify: Launch app and test SSH connection.

### Quick Access Accounts
- `GitHub`: https://github.com/
- `GitLab`: https://gitlab.com/
- `AWS Console`: https://aws.amazon.com/console/
- `Docker Hub`: https://hub.docker.com/

### Common Errors
- `docker: Cannot connect to the Docker daemon`
  Fix: Start Docker service, then run `docker ps`.
- `mvn: command not found`
  Fix: Install Maven and add it to `PATH`, then run `mvn -v`.
- `aws: command not found`
  Fix: Install AWS CLI and verify with `aws --version`.
- `Permission denied (publickey)` during SSH
  Fix: Add correct SSH key and verify with `ssh -T git@github.com`.
