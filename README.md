# Arash Rahimi — Platform Engineer & DevOps

> **Portfolio:** [arash00009.github.io](https://arash00009.github.io)  
> **LinkedIn:** [linkedin.com/in/arash-rahimi92](https://linkedin.com/in/arash-rahimi92/)  
> **Email:** arash_rahimi92@hotmail.com  
> **Available:** June 2026

---

## About This Repository

This is the source code for my personal portfolio website, built as a single-page HTML/CSS/JS application and hosted on GitHub Pages.

The site showcases my background, technical skills, work experience and certifications as I transition into the DevOps and Platform Engineering field after completing my vocational higher education (YH) at Lernia in Stockholm.

---

## About Me

I am a DevOps Engineer student at Lernia Yrkeshögskola (graduating June 2026) with a unique background that combines:

- **Platform Engineering** — Kubernetes, GitOps, IaC, Observability
- **Sociology** — BSc from Linnaeus University, 3+ years as career counsellor

Currently on LIA (internship) at **Cloudist AB** in Malmö, where I am designing and implementing a production-grade internal developer platform (IDP) based on Kubernetes, FluxCD, Prometheus and Grafana — fully Infrastructure-as-Code.

---

## Technical Skills

| Category | Technologies |
|----------|-------------|
| Container & Orchestration | Kubernetes, OpenShift, Docker, Podman, Helm |
| GitOps | FluxCD, ArgoCD |
| CI/CD | GitHub Actions, GitLab CI, Jenkins |
| Observability | Prometheus, Grafana, AlertManager, ELK |
| IaC & Automation | Terraform, Ansible, Bash, Python |
| Cloud | AWS, Azure, Cloudist/Virtuozzo |
| Linux | RHEL, Ubuntu, System Administration |
| Security | RBAC, GDPR, ISO 27001, Network Policies |
| Databases | MongoDB, PostgreSQL, Hadoop, Spark |

---

## Certifications

- 🔴 Red Hat OpenShift Administration I – DO180 (Oct 2025)
- 🔴 Red Hat OpenShift Development I: Podman – DO188 (Sep 2025)
- 🔴 Red Hat System Administration I & II – RH134
- ☁️ AWS Academy Graduate – Cloud Foundations
- 🔵 IBM Big Data Foundations
- 🍃 MongoDB Atlas Administrator Path
- 🍃 Introduction to MongoDB
- ⬡ Get Started with Databricks

---

## LIA Project — Cloudist Internal Developer Platform

**Period:** January – June 2026  
**Company:** Cloudist AB, Malmö  
**Role:** Platform Engineer Intern

### What I built

A production-grade internal Kubernetes-based developer platform (IDP) from scratch:

- **Kubernetes cluster** on Virtuozzo with RBAC and network policies
- **GitOps workflow** via FluxCD — changes in GitHub auto-apply to the cluster within minutes
- **Helm** for package management of all cluster applications
- **Prometheus** with Basic Auth for metrics collection and storage
- **Grafana** dashboards for real-time CPU, memory and network monitoring
- **Full IaC** — every configuration versioned in Git, reproducible from scratch

```bash
# GitOps sync status
$ flux get kustomizations
NAME        READY   STATUS
staging     True    Applied revision: main
monitoring  True    Applied revision: main

# All pods running
$ kubectl get pods -n monitoring
NAME                 STATUS    AGE
prometheus-0         Running   4d
grafana-6c8d2a       Running   4d
alertmanager-0       Running   4d
```

---

## Education

| Degree | Institution | Period |
|--------|-------------|--------|
| Qualified HVE Diploma – DevOps Engineer | Lernia Yrkeshögskola, Stockholm | 2024 – 2026 |
| BSc Sociology | Linnaeus University | 2017 – 2020 |

**8 VG (Merit)** grades across cloud technologies, database engineering, networking, Linux, information security, container technology and CI/CD.

---

## What Makes Me Different

Most platform engineers come from a purely technical background. I bring something harder to teach: a genuine understanding of **how organisations work**, **how people think**, and **how technology fits into the bigger picture**.

My sociology background combined with modern DevOps skills gives me an edge in stakeholder communication, risk assessment and building inclusive, high-performing teams.

---

## Contact

I am available for roles as **Platform Engineer**, **DevOps Engineer**, **SRE** or **Infrastructure Engineer** from June 2026.

- 📧 arash_rahimi92@hotmail.com
- 💼 [LinkedIn](https://linkedin.com/in/arash-rahimi92/)
- 🐙 [GitHub](https://github.com/arash00009)
- 📍 Landskrona, Sweden (open to remote / hybrid)

---

*Built with HTML, CSS and vanilla JavaScript. Hosted on GitHub Pages.*
