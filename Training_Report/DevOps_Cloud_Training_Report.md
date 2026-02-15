# DevOps & Cloud Training Report

## Report Scope
- This report captures day-wise learning and practical implementation from Day 01 to Day 16.
- The training path covers Linux administration basics, Git and GitLab workflow, build automation, Docker containerization, and AWS core services.
- The report is prepared from hands-on daily notes and aligned with the active training roadmap.

## Training Objectives
- Build strong command-line and Linux fundamentals required for DevOps.
- Learn source control workflows using Git and GitLab.
- Understand build and test lifecycle using Maven and Gradle.
- Containerize applications and manage container networking using Docker.
- Practice cloud deployment foundations on AWS using EC2, database, and storage services.

## Day-wise Detailed Progress

### Day 01 - Introduction and Environment Setup
- Established the initial development environment required for the training track.
- Installed Python FastAPI prerequisites to prepare for application-level practicals.
- Connected to remote environments using MobaXterm for terminal-based practice.
- Attended introductory session on DevOps lifecycle, cloud concepts, and expected training outcomes.
- Outcome: Base setup completed and foundational understanding of DevOps + Cloud direction established.

### Day 02 - Linux Fundamentals
- Started Linux learning with focus on terminal usage and operating system basics.
- Practiced essential commands for navigation and file operations such as `pwd`, `ls`, `cd`, `mkdir`, `touch`, `rm`, and `rmdir`.
- Understood relative and absolute path usage for directory traversal.
- Performed package index update using `sudo apt update`.
- Outcome: Built confidence in day-to-day Linux terminal usage.

### Day 03 - Linux CLI Deep Practice and Text Editing
- Continued CLI practice with advanced command usage and productivity shortcuts.
- Practiced command history, hidden files, and file content inspection commands such as `history`, `ls -a`, and `cat`.
- Learned system information commands like `uname -a`, `cat /etc/os-release`, `lscpu`, and `lsmem`.
- Practiced privilege escalation and user switching with `sudo` and `su`.
- Explored package managers (`apt`, `apt-get`, and `snap`) for software handling.
- Learned Vim editor workflow including insert/command modes, save/quit, search, replace, and navigation.
- Outcome: Improved Linux operational efficiency and editor-level control for server-side work.

### Day 04 - Advanced Linux Commands, Shell, and SSH
- Practiced advanced Linux command usage beyond basic navigation and file handling.
- Studied Linux shell behavior and command execution flow.
- Reviewed SSH concepts for secure remote machine access.
- Outcome: Prepared for remote administration and shell-driven DevOps operations.

### Day 05 - GitLab Project Setup
- Initiated first GitLab project with structured folder and file organization.
- Worked on static-site project artifacts for repository and pipeline readiness.
- Maintained key files such as `index.html`, `.gitlab-ci.yml`, and `README.md`.
- Outcome: Completed first structured project workspace on GitLab with CI-ready file layout.

### Day 06 - Git Branching Workflow
- Practiced branch-based development flow including branch creation and switching.
- Performed basic merge operations and studied conflict-handling approach.
- Reviewed branch strategy for cleaner collaboration and controlled changes.
- Outcome: Strengthened practical understanding of branching and merge lifecycle in Git.

### Day 07 - Java Maven Project Integration
- Created and used a `feature` branch for isolated development workflow.
- Added Java Maven application files and pushed code to GitLab repository.
- Used IntelliJ IDEA to initialize and manage Java project components.
- Installed JDK and configured required environment setup.
- Covered SQLite basics and ACID properties to understand database reliability fundamentals.
- Outcome: Completed Java project onboarding with SCM integration and supporting tooling setup.

### Day 08 - Maven, Gradle, and Spring Project Build
- Verified project availability and synchronization in GitLab before build execution.
- Installed and used Apache Maven for build and test operations in Maven-based projects.
- Installed and used Gradle for build and test operations in Gradle-based projects.
- Created a Spring Boot starter project via Spring Initializr and executed build in IntelliJ IDEA.
- Outcome: Understood build lifecycle and dependency-driven project compilation workflow.

### Day 09 - Docker Basics and Apache Container Build
- Practiced Docker image pull and container run operations.
- Pulled PostgreSQL image and ran container instance for database container familiarization.
- Built a custom Apache HTTPD image using Dockerfile and static content mapping.
- Ran container with host port mapping and validated web output on `localhost:8080`.
- Used Docker commands such as `docker ps`, `docker build`, `docker run`, and `docker exec`.
- Outcome: Learned end-to-end flow from Dockerfile authoring to containerized web content validation.

### Day 10 - Application Containerization
- Created Docker container setup for Java Maven application.
- Executed container and confirmed browser output for application validation.
- Began containerization workflow for PHP-based application.
- Supported peer troubleshooting during same containerization activity.
- Outcome: Gained confidence in adapting containerization approach across multiple application stacks.

### Day 11 - Docker Networking with MongoDB
- Created dedicated Docker network for isolated service communication.
- Deployed MongoDB container in custom network with root credentials.
- Practiced service startup, container checks, and network-based verification.
- Outcome: Understood container networking and service isolation basics for multi-service architecture.

### Day 12 - AWS EC2 Public and Private Instance Setup
- Created two EC2 instances on AWS for architecture practice.
- Configured one instance for public access and another for private access pattern.
- Reviewed practical implications of public/private placement in cloud environments.
- Outcome: Established foundational understanding of AWS compute provisioning and access design.

### Day 13 - AWS Database Provisioning and Connectivity
- Provisioned AWS resources for database interaction workflow.
- Created AWS MySQL database instance and linked usage with EC2-side command-line access.
- Practiced compute-to-database connection flow in cloud setup.
- Outcome: Built practical awareness of managed database usage with cloud compute nodes.

### Day 14 - AWS S3 Module Practice
- Covered Amazon S3 service fundamentals including object storage use cases.
- Worked through day module focused on storage-oriented implementation tasks.
- Reviewed how S3 fits into deployment workflows for static files, backups, and artifacts.
- Outcome: Improved understanding of cloud storage role within DevOps pipelines and deployments.

### Day 15 - EC2 + Apache Deployment Practice
- Continued Week 3 deployment track with EC2 and Apache web server focus.
- Practiced setup flow for Apache hosting on EC2 environment.
- Aligned deployment activities with prior Linux and Docker knowledge.
- Outcome: Strengthened infrastructure-level application hosting concepts on AWS compute.

### Day 16 - AWS Deployment Consolidation
- Worked on AWS deployment activities to combine compute, networking, and application hosting steps.
- Reinforced practical flow from infrastructure preparation to service validation.
- Consolidated key learnings from Week 3 deployment-focused sessions.
- Outcome: Completed Day 16 milestone with improved readiness for end-to-end cloud deployment tasks.

## Tools and Platforms Used
- Linux terminal (Bash)
- Git and GitLab
- IntelliJ IDEA
- Apache Maven
- Gradle
- Spring Boot and Spring Initializr
- Docker and Docker networking
- MongoDB and PostgreSQL containers
- AWS EC2, AWS RDS (MySQL), and AWS S3
- MobaXterm

## Overall Learning Outcomes (Day 01 to Day 16)
- Developed a strong Linux and command-line foundation for DevOps operations.
- Applied Git and GitLab workflows for version control and structured collaboration.
- Practiced project build and validation using Maven and Gradle tools.
- Containerized applications and worked with custom images, runtime commands, and networks.
- Performed core AWS tasks across compute, storage, and database services.
- Built progressive confidence in deployment-oriented thinking from local setup to cloud execution.

## Conclusion
- Training progress up to Day 16 is consistent and aligned with roadmap milestones.
- The practical-first approach helped connect concepts to implementation across Linux, CI/CD tooling, containers, and AWS.
- Next training phase should focus on deeper CI/CD automation, Infrastructure as Code, and project-level deployment integration.
