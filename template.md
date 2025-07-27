# 📄 Cross-team Alignment Document (CAD)

> **Purpose:** Define how two or more teams will collaborate on a shared capability or responsibility. This document outlines communication norms, ownership boundaries, SLAs, and decision-making paths to ensure a healthy, long-term working relationship.

---

## 🧭 1. Overview

**Purpose:** Describe the purpose of this CAD and why the relationship between these teams needs formal alignment.

**Example:**  
This CAD outlines the collaboration between the Mobile App Team and the Infrastructure Team to support continuous delivery of mobile backend services using Kubernetes. The goal is to align responsibilities, SLAs, and escalation paths to prevent confusion during deploys and environment setup.

---

## 👥 2. Teams Involved

**Purpose:** List the teams participating in this agreement and their primary functions.

**Example:**  
- **Mobile App Team** – Responsible for feature development and backend service logic.  
  - **Lead:** Jessica Chen (Engineering Manager)  
- **Infrastructure Team** – Manages Kubernetes, CI/CD tooling, and runtime environment.  
  - **Lead:** Marcus Fielding (SRE Manager)

---

## 🧱 3. Boundaries of Responsibility

**Purpose:** Clearly define what each team owns and does not own in this working relationship.

**Example:**  
- **App Team Owns:**  
  - Application code and API definitions  
  - Monitoring their service health via dashboards  
- **Infra Team Owns:**  
  - CI/CD pipelines and cluster maintenance  
  - Base container images and logging infrastructure  
- **Shared:**  
  - Release process coordination  
  - Scaling policies in production

---

## 🔄 4. Collaboration Norms

**Purpose:** Define how the teams interact on a regular basis — meetings, Slack channels, async workflows, etc.

**Example:**  
- Weekly standup on Tuesdays @ 10:30 CST  
- Shared Slack channel: `#app-infra-support`  
- Infra team commits to responding to requests within 1 business day  
- App team notifies infra of breaking changes 3 days in advance

---

## 🚨 5. Escalation & Support

**Purpose:** Define what to do when things break, are blocked, or need immediate attention.

**Example:**  
- P1 issues: Page SRE on-call via PagerDuty  
- P2/P3: Create a Jira ticket and ping in `#app-infra-support`  
- If no response in 24 hours, escalate to Engineering Director

---

## 📊 6. Success Metrics

**Purpose:** Define how you’ll measure whether this relationship is functioning well over time.

**Example:**  
- >90% attendance rate in weekly syncs  
- <2 missed deploy windows per quarter  
- >80% satisfaction score in cross-team health survey  
- <5 support tickets reopened due to unclear ownership

---

## 🔔 7. Change Management

**Purpose:** Describe how either team should communicate breaking changes, upgrades, or changes to interfaces/tooling.

**Example:**  
- Any breaking changes to CI/CD must be communicated at least 5 business days in advance.  
- Notification via Slack and Jira ticket.  
- App team must sign off on proposed downtime during deploys.

---

## 📅 8. Review & Update Cadence

**Purpose:** Define how often this CAD will be reviewed and refreshed.

**Example:**  
- Quarterly review led by Mobile App Tech Lead and Infra Team’s SRE lead.  
- Updated in Confluence by the owning parties after each review.  
- Feedback from both teams is solicited before making changes.

---

## 📁 9. Supporting Links

**Purpose:** Add links to docs, dashboards, runbooks, and team pages relevant to this CAD.

**Example:**  
- [CI/CD Pipeline Overview](https://company.com/docs/pipeline)  
- [Mobile Backend Deployment Guide](https://company.com/docs/deploy)  
- [Infra On-call Rotation](https://pagerduty.com/schedule/infra)  
- [SRE Runbook](https://company.com/runbooks/sre)
