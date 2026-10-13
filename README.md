# 🚀 Software Quality Assurance (QA) Master Plan
**Project Name:** QA Assistant System & Smart AI-Powered Bug Triage
**Team Name:** Bug Busters1 
**Academic Year:** 2026–2027
**Supervisor:** Ahmed Abd Elhafez  
**Assigned QA Engineer:** Abd Elrahman Esmat 

---

## 📌 Table of Contents
* [1. Project Overview](#-1-project-overview)
* [2. Key Performance Indicators (KPIs)](#-2-key-performance-indicators-kpis)
* [3. Software Test Plan (STP)](#-3-software-test-plan-stp)
* [4. Testing Strategy & Execution](#-4-testing-strategy--execution)
* [5. Risk Assessment & Mitigation](#-5-risk-assessment--mitigation)

---

## 📖 1. Project Overview
The **QA Assistant System & Smart AI-Powered Bug Triage** is an intelligent web-based platform designed to streamline software testing, bug tracking, and test case management. By integrating AI capabilities, the system assists QA teams in predicting bug severity, priority, potential duplicates, and suitable assignees, while keeping final human decision-making in full control.

---

## 📊 2. Key Performance Indicators (KPIs)

To evaluate both system quality and AI performance, the following strict and measurable KPIs have been established:

### A) System Quality KPIs
| KPI Metric | Formula / Calculation | Target Goal |
| :--- | :--- | :--- |
| **Test Case Pass Rate** | $(Passed \div Total) \times 100$ | $\ge 90\%$ |
| **Defect Density** | $Total\ Bugs \div Total\ Modules$ | $< 5$ |
| **Defect Removal Efficiency** | $(Bugs\ Found\ Before\ Release \div Total) \times 100$ | $\ge 95\%$ |
| **Test Coverage** | $(Tested\ Features \div Total\ Features) \times 100$ | $100\%$ |
| **Mean Time to Detect (MTTD)** | $Sum\ of\ Detection\ Times \div Total\ Bugs$ | $< 2$ Days |
| **Mean Time to Resolve (MTTR)** | $Sum\ of\ Resolution\ Times \div Total\ Bugs$ | $< 5$ Days |

### B) AI Performance KPIs
| KPI Metric | Formula / Calculation | Target Goal |
| :--- | :--- | :--- |
| **Classification Accuracy** | $(Correct\ AI\ Suggestions \div Total) \times 100$ | $\ge 80\%$ |
| **Duplicate Detection Precision** | $(True\ Duplicates \div Total\ Flagged\ as\ Duplicate) \times 100$ | $\ge 75\%$ |
| **Recommendation Acceptance Rate** | $(Accepted\ AI\ Suggestions \div Total) \times 100$ | $\ge 70\%$ |
| **Time Saved in Triage** | $Manual\ Triage\ Time - Automated\ Triage\ Time$ | $\ge 50\%$ Time Saved |

---

## 📋 3. Software Test Plan (STP)

### 🎯 Scope of Testing
* **In-Scope (Features to Test):**
  1. **Authentication & User Management:** Role-based access control (QA, Team Leader, Developer, PM).
  2. **Bug Tracking Module:** Creating, editing, filtering, and updating defect statuses.
  3. **AI Triage Module:** Validating AI severity/priority suggestions, duplicate detection, and automated summaries.
  4. **Test Case Management:** Creation, execution, and linking of test cases to defects.
  5. **Dashboard & Analytics:** Monitoring testing metrics and visual reports.
  6. **Backend APIs:** Endpoint validation and database consistency.

* **Out-of-Scope:**
  * Autonomous source code auto-fixing.
  * Production-scale deep learning model training from scratch.

---

## ⚙️ 4. Testing Strategy & Execution

| Testing Type | Description | Tools / Environment |
| :--- | :--- | :--- |
| **Manual UI Testing** | Verifying user interface workflows, layouts, and user experience. | Google Chrome, Edge, Firefox |
| **API Testing** | Testing backend endpoints, payloads, and response times. | Postman / Bruno |
| **AI Validation Testing** | Evaluating AI suggestion accuracy using diverse bug datasets. | Custom Test Bug Reports |
| **Regression Testing** | Ensuring bug fixes do not break existing system features. | Manual Execution Suite |

* **Environment:** PostgreSQL/MySQL, FastAPI/Flask backend, React Frontend, GitHub & Jira.
* **Entry Criteria:** Module deployed in test environment; requirements and test cases approved.
* **Exit Criteria:** 100% Critical test cases executed; Pass Rate $\ge 90\%$; Zero Blocker bugs open.

---

## ⚠️ 5. Risk Assessment & Mitigation

| Potential Risk | Severity | Mitigation Strategy |
| :--- | :--- | :--- |
| **Delayed Feature Delivery** | Medium | Start writing test cases and testing APIs independently without waiting for UI completion. |
| **Inaccurate AI Recommendations** | High | Prepare comprehensive test datasets to feed the AI and provide immediate feedback loops. |
| **Requirement Changes** | Medium | Maintain an agile testing mindset and update test plans iteratively. |

---
*Maintained by QA Engineer — Bug Busters1 Team*
