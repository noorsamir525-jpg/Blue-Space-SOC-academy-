# Blue Space

> **A little progress. A bigger universe.**

Blue Space is a guided learning workspace for building practical skills across **SOC, SIEM, SOAR, and Security AI**.

It combines a structured cybersecurity roadmap with hands-on practice, evidence tracking, readiness checkpoints, TryHackMe assignments, portfolio planning, and local progress tracking in a single browser-based application.

---

## Overview

Blue Space is built around a practical learning principle:

> **Learn → build → test → explain → keep the evidence.**

The included roadmap contains **50 modules** across two major parts:

- **Part 1 — SOC & Multi-Platform SIEM**
- **Part 2 — SOAR & Security AI**

The complete path is designed as a flexible long-term curriculum rather than a simple checklist. The roadmap recommends approximately **100 weeks** for full sequential completion, while the first SOC L1 application milestone comes after **S12**.

---

## Learning Tracks

Blue Space organizes the curriculum across these learning tracks:

1. Core SOC
2. Shared SIEM Foundations
3. Wazuh
4. Splunk Core
5. Splunk Enterprise Security
6. Microsoft Sentinel
7. Cross-Platform SIEM Comparison
8. SOAR
9. Security AI

The SIEM specialization follows the roadmap sequence:

`F01–F02 → W01–W04 → P01–P04 → E01–E03 → M01–M04 → X01`

---

## Main Features

### Guided Curriculum
- 50 structured learning modules
- Concepts, labs, scenarios, outputs, and self-checks
- Module prerequisites and track navigation
- Practical completion requirements rather than simple checkbox progress

### TryHackMe Practice
- Module-linked TryHackMe assignments
- Weekly practice organization
- Room search and aliases
- Progress tracking kept separate from curriculum validation

### Evidence Tracking
- Record practical evidence for labs and investigations
- Store descriptions, results, tools, environments, and reproduction steps
- Track implementation mode such as live lab, replay, simulation, or design-only
- Keep evidence references local to the browser

### Investigations
- Structured investigation records
- Evidence-focused workflow
- Convert investigation work into reusable evidence

### Readiness Checkpoints
Blue Space distinguishes between:

- **Scored Readiness Gates** — numerical assessment where the roadmap explicitly defines scoring
- **Evidence Checkpoints** — evidence-based completion where no numerical threshold is defined

Readiness gates are learning targets and do **not** guarantee employment, SOC L2 qualification, or production readiness.

### Portfolio Studio
- Module-specific project ideas
- GitHub/README planning
- LinkedIn draft preparation
- Evidence and sanitization review
- Private work can remain private; publishing is optional

### Search
Search across:
- Modules
- Practice
- Evidence
- Investigations
- Portfolio items

Search normalization supports common variations and aliases for room names and technical terms.

### Study Experience
- Dark and light themes
- Focus Mode
- Minimal Learning Mode
- Responsive desktop/mobile interface
- Keyboard-friendly controls
- Companion and optional gamification elements

### Backup & Recovery
- Export learner data
- Import validated backups
- Merge or replace supported learner state
- Recovery snapshots before destructive operations
- Visible storage status

---

## Privacy & Data Storage

Blue Space does **not** require a backend or user account.

Learner progress is stored in the browser using local storage when available.

That means:

- Your progress stays on your device/browser.
- Different browsers have separate progress.
- Different devices have separate progress.
- Clearing browser storage may remove progress.
- Use **Export Backup** regularly if your progress matters.

If persistent browser storage is unavailable, Blue Space can fall back to session-only storage and will warn the user.

No learner evidence files are automatically uploaded.

---

## Included Files

```text
.
├── index.html
├── roadmap.pdf
└── README.md
```

### `index.html`
The complete Blue Space web application.

### `roadmap.pdf`
The full practical SOC / SIEM / SOAR / Security AI roadmap used as the curriculum reference.

[Open the roadmap](./roadmap.pdf)

---

## Run Locally

No build process is required.

Place these files in the same folder:

```text
index.html
roadmap.pdf
```

Then open `index.html` in a modern browser.

For the most reliable behavior, especially for PDF access and browser storage, serving the files through HTTP/HTTPS is recommended.

---

## Curriculum Milestones

### Core SOC
**32 suggested weeks**

The first major application milestone is the **SOC L1 gate after S12**.

### SIEM Specialization
**36 additional suggested weeks**

Covers:
- Shared SIEM architecture and onboarding
- Wazuh
- Splunk Core
- Splunk Enterprise Security
- Microsoft Sentinel
- Cross-platform comparison

### SOAR + Security AI
**32 suggested weeks**

Covers:
- Reliable Python and APIs
- Docker and service operation
- Playbook design
- Workflow reliability
- Response policy and approvals
- SIEM/SOAR integration
- Statistics and ML
- LLM-assisted SOC workflows
- RAG
- Tool calling
- AI security
- Evaluation / MLOps / LLMOps
- Integrated capstone

---

## Learning Philosophy

Blue Space is designed around practical honesty.

A configured feature is not automatically a proven skill.

Learners should record:

- What was actually tested
- What was simulated
- What was replayed
- What remains untested
- The original evidence used to support conclusions

A copied successful walkthrough is not considered the final check. Labs should include expected behavior, near-matches, and failure cases where appropriate.

---

## Important Notes

- Some learning resources may require login or a paid subscription.
- Splunk Enterprise Security requires separate licensed access from Splunk Core.
- Cloud services may have costs, quotas, or account requirements.
- Use only authorized labs, owned systems, training environments, and sanitized data.
- Do not publish credentials, API keys, private logs, customer data, PII, or restricted lab material.

---

## Project Status

**Release Candidate / Feature Freeze**

Future changes should focus on:

- Confirmed bug fixes
- Security fixes
- Browser compatibility
- Broken resource links
- Curriculum corrections backed by the roadmap

Major feature expansion is intentionally out of scope for the current release.

---

## Disclaimer

Blue Space is an educational learning workspace.

Its completion indicators, readiness gates, portfolio tools, and progress metrics are internal learning aids. They do not guarantee employment, certification, SOC level qualification, or production readiness.

---

<p align="center">
  <strong>Blue Space</strong><br>
  <em>A little progress. A bigger universe.</em>
</p>
