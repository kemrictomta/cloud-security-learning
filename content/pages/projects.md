---
title: "Projects"
date: 2026-01-11
draft: false
---

Hands-on projects where I apply cloud, security, and engineering principles to real problems.  
Each project has a public repo — the code speaks for itself.

---

## secure-python-service — JSON Model Validator

**Status:** Active  
**Repo:** [github.com/kemrictomta/secure-python-service](https://github.com/kemrictomta/secure-python-service)

A Python CLI tool that validates JSON service-graph models (nodes, edges) and produces structured validation reports. Built to be deterministic, side-effect-free, and CI-embeddable.

**What it demonstrates:**
- Input validation with explicit trust boundaries
- Pure domain model (`Issue`, `Report`) with no side effects
- OWASP-oriented thinking applied to a real tool
- Dockerized, tested, automation-ready

**Skills:** Python · pytest · Docker · JSON schema validation · OWASP mindset

**Milestone logs:**  
→ [Initial validator with typed report and tests](../posts/secure-python-service/designing-a-validation-tool/)  
→ [Documentation & architecture expansion](../posts/secure-python-service/documentation-architecture-expansion/) *(draft)*

---

## Secure Cloud Baseline — *planned*

A minimal but secure cloud baseline: IAM policies, logging, and network hygiene defined as code.

**Skills:** Terraform · AWS · IAM · CloudTrail · least-privilege design

---

## Detection Starter Pack — *planned*

From validation to visibility — basic log collection, simple detection rules, and alert logic.

**Skills:** Log analysis · detection engineering · SIEM concepts
