We consider the Java language.

# Ecosystem Tools
Some Linters available for Java are:
- SpotBugs
- PMD
- Checkstyle
- Error Prone
Some Testers available for Java are:
- Selenium (primarily for browser automation tests)
- JUnit (to execute test suites of unit tests)
- TestNG (includes unit testing, e2e testing, and integration testing)
Popular build tools for Java are:
- Apache Ant
- Gradle
- Apache Maven

# Alternative CI tools
Alternatives to Jenkins and GH Actions include:
- Gitlab CI
- Azure DevOps
- CircleCI
- Bitbucket Pipelines
- AWS CodePipeline
- TravisCI
- Google Cloud Build
Many of the CI tools are developed by a cloud provider or git hosting provider in which case they integrate best with the platform created by that provider.

# Self/Cloud-Hosted
The determination depends on several factors such as:
- Is the code already cloud hosted?
- Are there special hardware/performance requirements?
- Does the CI pipeline need extra customization?

If the code is already cloud hosted, it is logical to use a cloud hosted CI tool from the same provider as it will provide good integration. In addition, this reduces the amount of config and setup that must be done.

However, if specialized hardware such as GPUs, high performance CPUs, or large amounts of RAM are needed, we cannot rely on cloud hosted solutions and must rent/buy a dedicated server with those resources.

Similarly, if the CI pipeline needs extra customization, a cloud hosted CI may not serve our requirements.