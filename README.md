# CI/CD Pipeline - Netflix Clone

## Project Overview

The **CI/CD Pipeline - Netflix Clone** project aims to build a Netflix clone featuring a collection of different movies. The project incorporates a robust Continuous Integration and Continuous Deployment (CI/CD) pipeline to streamline development, testing, and deployment processes.

## CI/CD Pipeline

The CI/CD pipeline is structured as follows:

1. **Local Development:** Development begins on a local computer, where code changes and features are developed and tested.

2. **Version Control:** Code changes are pushed to a Git repository, where version control is managed.

3. **Jenkins Script:** A Jenkins script automates the build and deployment process.

4. **Docker Image Creation:** Docker is used to create containerized applications. In this pipeline, a Docker image is generated.

5. **Google VM Deployment:** The Docker image is deployed to a Google Virtual Machine (VM).

6. **External IP Access:** The application becomes accessible via an external IP address.

## Hosting

- **WebApp:** The Netflix clone web application is hosted using Nginx, providing a reliable and scalable web server.

- **Content Storage:** Videos and thumbnail images are stored in an Nginx GitHub repository, ensuring efficient content management.

- **Catalogue Data:** Catalogue data, including movie information, is stored in MongoDB. A PyMongo Docker container hosts MongoDB on a VM, ensuring data persistence and accessibility.

