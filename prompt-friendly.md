You are generating a Cross-team Alignment Document (CAD). This document defines how two or more teams collaborate on a shared capability, service, or process. The goal is to ensure long-term clarity, effective handoffs, and accountability.

Use the following structure. For each section, follow the purpose and include realistic example content. Format everything in **Markdown**, including `mailto:` email links where appropriate.

---

# 📄 Cross-team Alignment Document (CAD)

> **Purpose:** Define how two or more teams will collaborate on a shared capability or responsibility. This document outlines communication norms, ownership boundaries, SLAs, and decision-making paths to ensure a healthy, long-term working relationship.

---

## 🧭 1. Overview

**Purpose:** Describe why this CAD is needed and what it aims to solve.

**Example:**  
This CAD outlines the collaboration between the Mobile App Team and the Infrastructure Team to support continuous delivery of mobile backend services using Kubernetes. The goal is to align responsibilities, SLAs, and escalation paths to prevent confusion during deploys and environment setup.

---

## 👥 2. Teams Involved

**Purpose:** List the teams participating in this agreement, their functions, and contact points.

**Instructions:**  
- List each team  
- Add a brief description of their function  
- Include:
  - Team contact email using Markdown syntax: `[email@domain.com](mailto:email@domain.com)`
  - Team lead name, role, and email  
  - At least one additional team member with role and email  

**Example:**

- **Mobile App Team** – Responsible for feature development and backend service logic.  
  - **Team Contact Email:** [mobile-dev@company.com](mailto:mobile-dev@company.com)  
  - **Lead:** Jessica Chen (Engineering Manager)  
    - [jessica.chen@company.com](mailto:jessica.chen@company.com)  
  - **Additional Contacts:**  
    - Alex Rivera (Sr. iOS Engineer) – [alex.rivera@company.com](mailto:alex.rivera@company.com)  
    - Priya Desai (Backend Lead) – [priya.desai@company.com](mailto:priya.desai@company.com)

- **Infrastructure Team** – Manages Kubernetes, CI/CD tooling, and runtime environment.  
  - **Team Contact Email:** [sre-team@company.com](mailto:sre-team@company.com)  
  - **Lead:** Marcus Fielding (SRE Manager)  
    - [marcus.fielding@company.com](mailto:marcus.fielding@company.com)  
  - **Additional Contacts:**  
    - Lena Torres (DevOps Engineer) – [lena.torres@company.com](mailto:lena.torres@company.com)  
    - Amir Patel (K8s Specialist) – [amir.patel@company.com](mailto:amir.patel@company.com)

---

## 🧱 3. Boundaries of Responsibility

**Purpose:** Clearly define what each team owns, what is shared, and what is not owned.

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

**Purpose:** Define how the teams interact day-to-day, including meetings, tools, and expectations.

**Example:**  
- Weekly standup on Tuesdays @ 10:30 CST  
- Shared Slack channel: `#app-infra-support`  
- Infra team responds to Slack requests within 1 business day  
- App team gives 3 business days’ notice before breaking changes

---

## 🚨 5. Escalation & Support

**Purpose:** Define what to do when issues arise or urgent decisions are needed.

**Example:**  
- P1 issues: Page SRE on-call via PagerDuty  
- P2/P3: File a Jira ticket and notify in `#app-infra-support`  
- If no response in 24 hours, escalate to Engineering Director  
- Shared incident postmortems for joint issues

---

## 📊 6. Success Metrics

**Purpose:** Identify how to measure whether the working relationship is functioning well.

**Example:**  
- >90% attendance rate in weekly syncs  
- <2 missed deploy windows per quarter  
- >80% satisfaction score in cross-team health survey  
- <5 reopened support tickets due to unclear ownership

---

## 🔔 7. Change Management

**Purpose:** Define how each team communicates changes that could impact the other.

**Example:**  
- Breaking changes must be communicated 5 business days in advance  
- Notification through Jira ticket + Slack message  
- Approval required from impacted team’s tech lead  
- Infra team provides rollout plans for major version changes

---

## 📅 8. Review & Update Cadence

**Purpose:** Ensure the CAD remains current and relevant.

**Example:**  
- Reviewed quarterly by App Tech Lead and Infra SRE Lead  
- Updates made in Confluence with changelog notes  
- Feedback requested via Slack thread prior to review

---

## 📁 9. Supporting Links

**Purpose:** List relevant documentation and tools.

**Example:**  
- [CI/CD Pipeline Overview](https://company.com/docs/pipeline)  
- [Mobile Backend Deployment Guide](https://company.com/docs/deploy)  
- [Infra On-call Rotation](https://pagerduty.com/schedule/infra)  
- [SRE Runbook](https://company.com/runbooks/sre)
