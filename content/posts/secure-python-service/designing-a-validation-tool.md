---
title: "Milestone: Initial JSON Model Validator with Typed Report and Tests"
date: 2026-01-14
tags: ["secure-python-service", "python", "validation"]
---

First functional commit for [secure-python-service](https://github.com/kemrictomta/secure-python-service) — a JSON model validator that checks service-graph definitions and produces structured reports.

**Commit:** `678f64e` — *Initial JSON model validator with typed report and tests*

**What was delivered:**
- `domain.py` — `Issue(path, message, severity)` and `Report(ok, issues)` dataclasses
- `validator.py` — `validate_model()` enforces JSON object type and required fields (`name`, `version`, `nodes`, `edges`)
- `architecture.md` — initial architecture document with components, data format, and exit codes
- 3 passing unit tests (invalid type, missing fields, valid payload)
- Project scaffolding: Dockerfile, requirements.txt, GitHub Actions workflow, .gitignore

<!-- TODO: add diagram or screenshot -->

**Repo:** [secure-python-service](https://github.com/kemrictomta/secure-python-service)
