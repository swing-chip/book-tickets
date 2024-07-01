# Getting Started

## Tech Stack

- **Languages & Frameworks**
    - Java, Spring Framework (MVC, WebFlux, Batch), JPA, MySQL
    - Gradle, gRPC
- **Testing, Build, Deployment**
    - JUnit, Git Actions
- **Project Management**
    - GitHub Projects for issue tracking
- **Documentation**
    - GitHub Pages
- **Git Branch Strategy**
    - Create an issue and use the issue ticket number for branch names (e.g., `BE-1`).
    - Develop on the branch, submit a PR, and merge after approval.
    - Deploy to the `master` branch.
    - **Git Commit Message Convention**
        - Follow conventions from:
            - [Git Commit Message Conventions](https://gist.github.com/stephenparish/9941e89d80e2bc58a153)
            - [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/)
    - **Squash and Merge**
        - Use squash merge for PRs.

## Configuration

- **IDE**
    - JetBrains IntelliJ
- **Development Environment**
    - Docker Dev Container
- **Java Version**
    - Java 17