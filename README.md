# 🚀Three Tier Devops Azure

This repository acts as a **Super-Repo (Git Submodule Manager)** that links to:

* **Application Source Code** → [`spring-react-devops-appservice`](https://github.com/hasanashab/spring-react-devops-appservice)
* **Infrastructure as Code (Terraform)** → [`spring-react-devops-appservice-infra`](https://github.com/hasanashab/spring-react-devops-appservice-infra)


---

## 📦 DevOps Workflow Overview

* **Infrastructure Provisioning (infra/):**

  * Terraform scripts to provision Azure resources (App Service, MySQL, Deployment Slots, etc.)
* **Application Code (src/):**

  * React Frontend
  * Spring Boot Backend (REST APIs)
  * Dockerized Microservices

---

## 🧪 Deployment Strategy

* **Blue-Green Deployment** using Azure App Service Deployment Slots.
* CI/CD pipelines managed through **GitHub Actions**.
* Infrastructure managed as **Code with Terraform**.

---

## 💡 Why a Super-Repo?

This structure allows:

* **Modular development** for App and Infra.
* Easier to navigate to the project.
* Clear separation of application logic and infrastructure code while keeping them linked.

---


## 🤝 Contributions & Feedback

Feel free to suggest improvements or raise issues!
