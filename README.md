# CI/CD Pipeline with Jenkins, SonarQube, and Docker on AWS

This repository demonstrates the implementation of a **CI/CD pipeline** using **Jenkins**, **SonarQube**, and **Docker** on **AWS**. The setup automates the process of building, testing, and deploying applications. For detailed instructions, refer to the step-by-step guide available [here](https://mahesh1215.hashnode.dev/a-beginners-guide-to-setting-up-a-cicd-pipeline-with-jenkins-sonarqube-and-docker-on-aws).

## 🚀 Project Overview

This project covers the following DevOps practices:

- **Jenkins**: Automates the continuous integration and deployment (CI/CD) pipeline.
- **SonarQube**: Performs static code analysis to ensure code quality and security.
- **Docker**: Packages applications into containers for consistent deployment environments.
- **AWS**: Hosts and deploys the application in the cloud.

## 🧑‍💻 Setup Instructions

1. Clone the repository:

  ```bash
   git clone https://github.com/mahesh-diwan/Devops-Project1.git
   cd Devops-Project1
   ```

2. **Docker**: Build and run the Docker container locally:

  ```bash
  docker build -t my-app .
  docker run -p 8080:80 my-app
  ```

3. **Jenkins**: Set up Jenkins with the provided Jenkinsfile to automate the CI/CD process. Follow the steps in the guide to configure Jenkins and integrate it with Docker and SonarQube.

For detailed steps on setting up the entire CI/CD pipeline, check the guide [here](https://mahesh1215.hashnode.dev/a-beginners-guide-to-setting-up-a-cicd-pipeline-with-jenkins-sonarqube-and-docker-on-aws).

## 🌟 Contributing

Feel free to fork this repository and submit pull requests to improve or add features. Contributions are welcome!
