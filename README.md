# 👋 Hi, I'm Villandry Calderón

### DevSecOps Engineer | Cloud Security | Platform Engineering

> **Secure by design. Automated by default. Continuously improving.**

Computer Engineer with 5+ years of experience in enterprise and banking environments, focused on **DevSecOps, Cloud Security, CI/CD Security and Infrastructure as Code**.

I design and automate secure delivery platforms across **AWS and Azure**, integrating security controls into the software development lifecycle and working across development, infrastructure and security teams.

My current technical focus is the convergence of:

**DevOps → DevSecOps → Application Security → Cloud Security → IAM**

---

## 🛡️ Security & DevSecOps

![DevSecOps](https://img.shields.io/badge/DevSecOps-0A0A0A?style=for-the-badge\&logo=github\&logoColor=white)
![Cloud Security](https://img.shields.io/badge/Cloud%20Security-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![Application Security](https://img.shields.io/badge/Application%20Security-FF6B35?style=for-the-badge\&logo=owasp\&logoColor=white)
![CI/CD Security](https://img.shields.io/badge/CI%2FCD%20Security-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)
![IaC Security](https://img.shields.io/badge/IaC%20Security-844FBA?style=for-the-badge\&logo=terraform\&logoColor=white)

### Security Stack

| Domain                      | Technologies                                                    |
| --------------------------- | --------------------------------------------------------------- |
| **SAST / Code Security**    | Veracode · SonarCloud · CodeQL                                  |
| **Dependency Security**     | Dependabot                                                      |
| **CI/CD Security**          | GitHub Actions · Azure Pipelines · Azure DevOps                 |
| **Cloud Security**          | AWS · Azure · IAM · KMS · CloudWatch                            |
| **Infrastructure Security** | Terraform · Kubernetes · AKS · EKS                              |
| **Identity & Access**       | PingOne · PingAM · IAM                                          |
| **Security Platforms**      | Check Point · Spectral                                          |
| **Secure SDLC**             | Security Gates · Vulnerability Management · Security Automation |

---

## ☁️ Cloud & Platform Engineering

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge\&logo=terraform\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)

**AWS:** IAM · KMS · Lambda · CloudWatch · EKS · Networking
**Azure:** AKS · Azure DevOps · Azure Pipelines · Cloud Infrastructure
**Infrastructure:** Terraform · HCL · Kubernetes · Docker
**Automation:** GitHub Actions · Azure Pipelines · Bash · Python · YAML

---

# 🔐 DevSecOps Architecture

```text
                         ┌──────────────────────┐
                         │     Developer        │
                         │   Git / Pull Request │
                         └──────────┬───────────┘
                                    │
                                    ▼
                    ┌────────────────────────────┐
                    │       GitHub Enterprise    │
                    │   Branch Protection / PRs  │
                    └─────────────┬──────────────┘
                                  │
                                  ▼
                    ┌────────────────────────────┐
                    │       GitHub Actions       │
                    │      CI/CD Orchestration   │
                    └─────────────┬──────────────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
              ▼                   ▼                   ▼
        ┌───────────┐       ┌───────────┐       ┌─────────────┐
        │  CodeQL   │       │ SonarCloud │       │ Dependabot  │
        │   SAST    │       │ Code Qual. │       │ Dependencies│
        └─────┬─────┘       └─────┬─────┘       └──────┬──────┘
              │                   │                    │
              └───────────────────┼────────────────────┘
                                  ▼
                       ┌─────────────────────┐
                       │   Security Gates    │
                       │ Vulnerabilities /   │
                       │ Quality / Policies  │
                       └──────────┬──────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │      Terraform      │
                       │ Infrastructure as   │
                       │        Code         │
                       └──────────┬──────────┘
                                  │
                                  ▼
                    ┌────────────────────────────┐
                    │        AWS / Azure         │
                    │ Kubernetes · IAM · KMS     │
                    │ Networking · Monitoring    │
                    └─────────────┬──────────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │ Monitoring &        │
                       │ Vulnerability Mgmt  │
                       └─────────────────────┘
```

The objective is to make security part of the delivery process rather than a final manual checkpoint.

---

# 🧰 Security Tooling

### Veracode

Hands-on experience integrating **Veracode SAST into Azure Pipelines**, including branch-based analysis, security controls, scheduled builds and vulnerability tracking.

### SonarCloud

Integration of code quality and security analysis into CI/CD pipelines as part of repository and delivery standards.

### Dependabot

Dependency monitoring and vulnerability management integrated into repository workflows.

### GitHub Advanced Security

Currently expanding my expertise in:

* CodeQL
* Secret scanning
* Dependency security
* Security workflows
* Code scanning
* Secure repository configuration

### Check Point & Spectral

Expanding my security toolkit across cloud, application and infrastructure security.

### PingOne / PingAM

Developing expertise in **Identity & Access Management**, authentication and identity security through Ping Identity training and hands-on learning.

---

# 🚀 Featured Projects

## 🔐 DevSecOps Secure Pipeline

**GitHub Actions · CodeQL · SonarCloud · Dependabot · Terraform**

A demonstration CI/CD platform implementing security controls throughout the software delivery lifecycle.

**Security workflow:**

```text
Pull Request
     ↓
Unit Tests
     ↓
CodeQL
     ↓
SonarCloud
     ↓
Dependency Analysis
     ↓
Terraform Validation
     ↓
Security Gates
     ↓
Deployment
```

The project demonstrates how multiple security controls can work together inside a modern CI/CD pipeline.

---

## ☁️ Secure Infrastructure as Code

**Terraform · AWS · IAM · KMS · CloudWatch**

Infrastructure-as-Code project focused on secure cloud provisioning, least-privilege access, encryption and monitoring.

Key objectives:

* Reusable Terraform modules
* Secure IAM policies
* Encryption with KMS
* Infrastructure validation
* CI/CD-driven Terraform plans
* Separation of plan and apply
* Secure handling of credentials

---

## 🔑 Identity & Access Security Lab

**PingOne · PingAM · IAM**

A learning lab focused on modern identity security concepts:

* Authentication
* Authorization
* Identity lifecycle
* Access policies
* Federation concepts
* Secure application integration

---

# 🎓 Certifications & Professional Development

### Current / Completed Training

* **PingAM Core Skills**
* **PingOne Advanced Identity Cloud – Micro Core Skills**
* **DevSecOps: Building a Secure Continuous Delivery Pipeline**
* **Application Security in DevSecOps**
* **Ciberseguridad: Implement incident management processes**
* AWS / Azure technical training and badges
---

# 💼 Professional Experience

### BAC Credomatic — DevSecOps / Platform Engineering

**2021 – Present**

* Designed and integrated Veracode SAST into Azure Pipelines.
* Implemented CI/CD security controls and vulnerability tracking.
* Built and maintained Terraform infrastructure across AWS and Azure.
* Worked with AKS, EKS, IAM, KMS, Lambda and CloudWatch.
* Supported migration from Azure Repos to GitHub Enterprise.
* Supported migration from Jenkins to Azure Pipelines and later GitHub Actions.
* Established repository standards integrating SonarCloud, Veracode and Dependabot.
* Supported secure delivery practices for a mobile banking platform.
* Acted as an internal technical reference for Veracode and CI/CD security controls.
* Participated in vulnerability remediation initiatives and security-focused engineering activities.

---

# 📚 Currently Learning

```text
GitHub Advanced Security
        │
        ├── CodeQL
        ├── Secret Scanning
        ├── Dependency Security
        └── Security Workflows
                 │
                 ▼
        Application Security
                 │
                 ▼
          Cloud Security
                 │
                 ▼
          Identity & Access
                 │
                 ▼
        Security Automation
```

---

# 🎯 Professional Direction

I am interested in engineering roles where **platform engineering, cloud infrastructure, automation and cybersecurity intersect**.

My long-term goal is to design platforms where:

> **Infrastructure, application delivery and security operate as one engineering discipline.**

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/villandrycalderon/)

---

### Secure by design.

### Automated by default.

### Continuously improving.
