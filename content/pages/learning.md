---
title: "Security & Cloud Learning"
date: 2026-01-11
draft: false
---

I document my learning journey in **cloud** and **cybersecurity engineering** through **hands-on labs**, focused writeups, and small but intentional projects.

I start with a **static learning page** to clarify objectives and scope.  
Once a security or cloud objective is clear, I build **minimal, purpose-driven tooling or infrastructure** to support it — nothing more, nothing less.

---

## Now
**Focus (current period)**

- **Cloud:** IAM fundamentals, networking basics (VPC, routing, DNS, TLS)
- **Security:** trust boundaries, validation mindset, OWASP-oriented thinking
- **DevOps:** reproducibility habits (Docker, tests, CI as a gate)

**Weekly routine**
- 2 labs/week → concise technical notes
- 1 concept/week → summarized reasoning + references
- 1 focused project/month → documented design + deliverables

---

## Roadmap
### Cloud Foundations
- [ ] AWS fundamentals: IAM, EC2, S3
- [ ] Networking: VPC, subnets, routing, security groups
- [ ] Observability basics: CloudTrail / CloudWatch
- [ ] IaC foundations: Terraform (structure before scale)

### DevOps Foundations
- [ ] Git discipline: clean commits, readable history, meaningful messages
- [ ] Docker: build/run images, volumes, networking
- [ ] CI/CD: GitHub Actions (test → validate → enforce)
- [ ] Kubernetes basics (later): k3s / minikube, core primitives

### Security Foundations
- [ ] Input validation & trust boundaries
- [ ] Linux fundamentals: permissions, services, logs
- [ ] Networking basics: DNS, TLS, HTTP, common ports
- [ ] Web security concepts: OWASP Top 10 (mindset, not tools)
- [ ] Detection fundamentals (later): logs → signals → alerts

---

## Tools I Use
### Cloud & DevOps
- Git & GitHub
- Docker
- GitHub Actions
- Terraform (in progress)

### Security
- Linux (Ubuntu / Kali labs)
- Wireshark
- Nmap
- Burp Suite (learning)

---

## Labs & Writeups
### Completed
- ✅ Architecture validation: input contracts & rule-based checks

### In progress
- ⏳ Type-safe validation rules and automation-friendly output

### Next
- ⏭️ CLI-based validation and CI integration

---

## Projects
### 1) Architecture Validation Tool (active)
**Goal:** design and implement a validation tool that enforces **explicit contracts and trust boundaries** on architecture/configuration models.

This project applies engineering rigor to a security-relevant problem:
- untrusted inputs
- deterministic validation
- rule-based enforcement
- automation and CI readiness

**Deliverables:**
- Python-based validator with clear domain model
- rule-driven validation logic with tests
- documented design decisions and roadmap

Related writeup:  
→ **Designing a Validation Tool — Applying Engineering Rigor to Cloud & Security Learning**

---

### 2) Secure Cloud Baseline (planned)
**Goal:** define a minimal but secure cloud baseline (IAM, logging, network hygiene).

**Deliverables:**
- Terraform repository
- architecture diagram
- short rationale (“what is enforced and why”)

---

### 3) Detection Starter Pack (planned)
**Goal:** move from validation to **visibility and detection**.

**Deliverables:**
- basic log collection
- simple detection rules
- screenshots + explanatory writeup

---

## Professional Case Study
I also documented a sanitized professional project that introduced me to **Python**, **Docker**, and **graph-based modeling** (Neo4j/Cypher), with a strong emphasis on architecture and validation logic.

→ Go to: **/pages/case-study/**
