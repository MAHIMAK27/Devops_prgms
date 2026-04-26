# DevOps Lab – Gradle and Maven (VTU 6th Sem)

## Overview

This repository contains my work and understanding of build automation tools, specifically **Maven** and **Gradle**, as part of the DevOps laboratory course in the 6th semester (VTU). The focus is on learning how modern software projects are built, managed, and automated using industry-standard tools.

## Introduction to Build Automation

In software development, build automation tools simplify and standardize the process of compiling code, managing dependencies, running tests, and packaging applications. Instead of manually executing multiple steps, tools like Maven and Gradle automate the entire lifecycle, ensuring consistency and efficiency.

## Apache Maven

Maven is a widely used build automation and project management tool based on the concept of a **Project Object Model (POM)**.
<img width="1600" height="738" alt="jenkins dashboard" src="https://github.com/user-attachments/assets/581365bd-51ca-4414-8cbd-d7cf946cd669" />

### Key Concepts:

* **POM (pom.xml):** Central configuration file that defines project structure, dependencies, plugins, and build lifecycle.
* **Convention over Configuration:** Maven follows a standard directory structure, reducing the need for manual configuration.
* **Dependency Management:** Automatically downloads required libraries from repositories.
* **Build Lifecycle:** Includes phases such as `validate`, `compile`, `test`, `package`, `install`, and `deploy`.

### Advantages:

* Easy to learn due to its structured approach
* Strong dependency management system
* Large community support

### Limitations:

* XML configuration can become verbose
* Less flexible compared to Gradle

## Gradle

Gradle is a modern build automation tool that combines the best features of Maven and Ant while providing more flexibility.

### Key Concepts:

* **Build Scripts:** Written in Groovy or Kotlin DSL (build.gradle / build.gradle.kts)
* **Incremental Builds:** Only rebuilds parts of the project that have changed
* **Dependency Management:** Similar to Maven but more flexible
* **Custom Tasks:** Developers can define their own build logic

### Advantages:

* Faster builds due to incremental execution
* More flexible and customizable
* Supports multi-project builds efficiently

### Limitations:

* Slightly steeper learning curve
* Requires understanding of scripting

## Maven vs Gradle

| Feature        | Maven         | Gradle                      |
| -------------- | ------------- | --------------------------- |
| Configuration  | XML-based     | Groovy/Kotlin-based         |
| Flexibility    | Less flexible | Highly flexible             |
| Performance    | Slower        | Faster (incremental builds) |
| Learning Curve | Easier        | Moderate                    |

## Jenkins Integration

As part of the experiment, Jenkins was used to automate the build process of a Maven project.

### Key Concepts of Jenkins:

* **Continuous Integration (CI):** Automatically builds and tests code whenever changes are made
* **Jobs/Pipelines:** Define tasks such as building, testing, and deploying
* **Plugins:** Extend Jenkins functionality (e.g., Maven integration plugin)

### Workflow Followed:

1. Setup Jenkins on Ubuntu
2. Configure Maven environment
3. Create a simple Maven project
4. Configure a Jenkins job to build the project
5. Execute and monitor build process

## Importance in DevOps

Build tools like Maven and Gradle are essential in DevOps because they:

* Automate repetitive tasks
* Ensure consistency across environments
* Integrate with CI/CD pipelines
* Improve development speed and reliability

## Conclusion

This experiment provided practical exposure to build automation tools and their integration with Jenkins. Understanding Maven and Gradle is crucial for implementing efficient DevOps practices, as they form the foundation for continuous integration and delivery pipelines.

This repository reflects my learning and hands-on experience with build tools and automation in a DevOps environment.
