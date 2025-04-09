# DevOps Portfolio

Welcome to my DevOps portfolio! This repository highlights the projects I completed, showcasing my hands-on experience with DevOps tools and practices.

- [TWN DevOps Projects](#twn-devops-projects)  
- [The University of Chicago](#the-university-of-chicago)  
- [Other DevOps Projects](#other-devops-projects)

---

## TWN DevOps Projects

Here are the projects I completed during the TWN DevOps Bootcamp:

### Build Automation & CI/CD with Jenkins <img src="./assets/twn-devops-projects/01-jenkins/jenkins-icon.png" alt="Project Tools" width="35" align="left" />

<details>
  <summary><strong> 🟢 Demo Project: Install Jenkins on DigitalOcean</strong></summary><br>

  **Technologies Used**:
  Jenkins, Docker, DigitalOcean, Linux <img src="./assets/twn-devops-projects/01-jenkins/project-tools-icons1.png" alt="Project Tools" width="200" align="right" />

  **Project Description:**
  - Create an Ubuntu server on DigitalOcean.
  - Set up and run Jenkins as a Docker container.
  - Initialize Jenkins and configure it for CI/CD.
  For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/twn-devops-projects/01-jenkins/Demo_Project_Install_Jenkins_on_DigitalOcean.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Demo Project: Create a CI Pipeline with Jenkinsfile (Freestyle, Pipeline, Multibranch Pipeline) </strong></summary><br>

**Technologies Used:**
Jenkins, Docker, Linux, Git, Java, Maven <img src="./assets/twn-devops-projects/01-jenkins/project-tools-icons2.png" alt="Project Tools" width="300" align="right" />

**Project Description:**
CI Pipeline for a Java Maven application to build and push to the repository:
- Install Build Tools (Maven, Node) in Jenkins
- Make Docker available on Jenkins server
- Create Jenkins credentials for a Git repository
- Create different Jenkins job types (Freestyle, Pipeline (with Jenkinsfile), Multibranch pipeline (with Jenkinsfile)) for the Java Maven project to:
  - Connect to the application’s Git repository
  - Build Jar
  - Build Docker Image
  - Push to a private DockerHub repository

Below is a visual representation of the pipeline:

![Pipeline](./assets/twn-devops-projects/01-jenkins/Pipeline_diagram.png)

For setup guidance, please refer to the attached [Setup Guide PDF](./assets/twn-devops-projects/01-jenkins/Setup_Guide_Demo_Project_Create_a_CI_Pipeline_with_Jenkinsfile.pdf).  

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/twn-devops-projects/01-jenkins/Demo_Project_Create_a_CI_Pipeline_with_Jenkinsfile.pdf) document.

If you would like to explore the code for this project, please visit this [GitLab repository](https://gitlab.com/twn-devops-projects/jenkins/java-maven-app/-/tree/main?ref_type=heads).

---
</details>

<details>
  <summary><strong>🟢 Demo Project: Create a Jenkins Shared Library</strong></summary><br>

**Technologies Used**:  
Jenkins, Groovy, Docker, Git, Java, Maven <img src="./assets/twn-devops-projects/01-jenkins/project-tools-icons3.png" alt="Project Tools" width="300" align="right" />

**Project Description:**
- Create a separate Git repository for the Jenkins Shared Library project
- Create functions in the JSL to use in the Jenkins pipeline
- Integrate and use the JSL in Jenkins Pipeline (globally and for a specific project in Jenkinsfile)

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/twn-devops-projects/01-jenkins/Demo_Project_Create_a_Jenkins_Shared_Library.pdf) document.

If you would like to explore the code for this project, please visit this [GitLab repository](https://gitlab.com/twn-devops-projects/jenkins/jenkins-shared-library).

---
</details>

<details>
  <summary><strong>🟢 Demo Project: Configure Webhook to trigger CI Pipeline automatically on every change</strong></summary><br>

**Technologies Used**:  
Jenkins, Docker, GitLab, Git, Java, Maven <img src="./assets/twn-devops-projects/01-jenkins/project-tools-icons4.png" alt="Project Tools" width="300" align="right" />

**Project Description:**
- Install GitLab Plugin in Jenkins
- Configure GitLab access token and connection to Jenkins in GitLab project settings
- Configure Jenkins to trigger the CI pipeline whenever a change is pushed to GitLab

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/twn-devops-projects/01-jenkins/Demo_Project_Configure_Webhook_to_trigger_CI_Pipeline_automatically_on_every_change.pdf) document.

Note: There is no **GitLab repository** for this project since it focuses on setting up the Webhook.

---
</details>

<details>
  <summary><strong>🟢 Demo Project: Dynamically Increment Application version in Jenkins Pipeline</strong></summary><br>

**Technologies Used**:  
Jenkins, Docker, GitLab, Git, Java, Maven <img src="./assets/twn-devops-projects/01-jenkins/project-tools-icons4.png" alt="Project Tools" width="300" align="right" />

**Project Description:**
- Configure CI step: Increment patch version
- Configure CI step: Build Java application and clean old artifacts
- Configure CI step: Build image with dynamic Docker Image Tag
- Configure CI step: Push image to private DockerHub repository
- Configure CI step: Commit version update of Jenkins back to Git repository
- Configure Jenkins pipeline to avoid commit loop by not triggering on version bump commits

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/twn-devops-projects/01-jenkins/Demo_Project_Dynamically_Increment_Application_version_in_Jenkins_Pipeline.pdf) document.

If you would like to explore the code for this project, please visit this [GitLab repository](https://gitlab.com/twn-devops-projects/jenkins/java-maven-app/-/tree/jenkins-jobs?ref_type=heads).

---
</details>


---
---
## The University of Chicago

Here are the projects I completed during when studying at The University of Chicago:


<details>
  <summary><strong> 🟢 Setting up a Virtual Machine and Getting Started</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

  For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_1_Setting_up_a_Virtual_Machine_and_Getting_Started.pdf) document.

  ---
</details>

<details>
  <summary><strong> 🟢 Cloud Computing</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_2_Cloud_Computing.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Create an Open-Source Software</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_3_Create_an_Open-Source_Software.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Git Repository</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_4_Git_Repository.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Creating a CI Environment</strong></summary><br>

  **Technologies Used:**

  **Project Description:**


For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_5_Creating_a_CI_Environment.pdf) document.

---
</details>


<details>
  <summary><strong> 🟢 Deploying with Docker</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_6_Deploying_with_Docker.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Creating an Amazon RDS MySQL Database for Software Configuration</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_7_Creating_an_Amazon_RDS_MySQL_Database_for_Software_Configuration.pdf) document.

---
</details>

<details>
  <summary><strong> 🟢 Datadog Dashboard</strong></summary><br>

  **Technologies Used:**

  **Project Description:**

For detailed **steps and processes** followed during the project, please refer to the attached [PDF](./assets/the-university-of-chicago/Assignment_8_Datadog_Dashboard.pdf) document.

---
</details>

---
---

## Other DevOps Projects

These are additional projects I worked on to expand my DevOps expertise:


---
