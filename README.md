# 🛡️ Sneaker Marketplace - PASTA Threat Model

![Google Cybersecurity Certificate](https://img.shields.io/badge/Google-Cybersecurity_Certificate-blue?style=for-the-badge&logo=google)
![Threat Modeling](https://img.shields.io/badge/Skill-Threat_Modeling-critical?style=for-the-badge)
![PASTA Framework](https://img.shields.io/badge/Framework-PASTA-success?style=for-the-badge)

## 📖 Project Overview

This project is part of my professional portfolio, developed during the **Google Cybersecurity Professional Certificate** program. It showcases a practical, hands-on application of threat modeling using the **PASTA (Process for Attack Simulation and Threat Analysis)** framework.

> **Scenario:** As a Cybersecurity Specialist for a growing sneaker enthusiast company, the goal is to analyze the architecture of a new mobile marketplace application, identify potential threats and vulnerabilities, and recommend actionable security controls prior to deployment.

---

## 🔍 Methodology (The 7 Stages of PASTA)

The PASTA framework is a risk-centric threat modeling approach. Here is how I applied its seven stages to the sneaker marketplace application:

*   **1️⃣ Define Business and Security Objectives:** Identified core business goals such as secure transactions, strict data privacy, and mandatory PCI-DSS compliance.
*   **2️⃣ Define Technical Scope:** Mapped out critical infrastructure components, including APIs, SQL databases, and robust cryptographic protocols (SHA-256, AES).
*   **3️⃣ Decompose Application:** Analyzed the data flow (DFD) mapping interactions between users, product search APIs, and the backend database.
*   **4️⃣ Threat Analysis:** Identified specific, highly probable threats, notably **SQL Injections** and **Session Hijacking**.
*   **5️⃣ Vulnerability Analysis:** Pinpointed underlying weaknesses, such as the lack of prepared statements and the allowance of weak login credentials.
*   **6️⃣ Attack Modeling:** Evaluated attack trees to understand the exact paths a malicious actor might take to compromise sensitive user data.
*   **7️⃣ Risk Analysis & Impact:** Proposed comprehensive, business-aligned mitigation strategies, including parameterized queries, Multi-Factor Authentication (MFA), and enforcing the Principle of Least Privilege.

---

## 📂 Files Included

| File | Description |
| :--- | :--- |
| 📄 [`PASTA_Threat_Model_Report.pdf`](./PASTA_Threat_Model_Report.pdf) | The complete, finalized security report detailing all seven stages of the analysis. |
| 📊 `PASTA-data-flow-diagram.pptx` | The architectural data flow diagram provided for the scenario. |
| 🌳 `PASTA-attack-tree.pptx` | The sample attack tree diagram used for attack modeling. |



---

## 🛠️ Skills & Competencies Demonstrated

- **Threat Modeling & Risk Assessment:** Ability to identify and quantify risks in a proposed software architecture.
- **Framework Implementation:** Practical application of the PASTA methodology.
- **Vulnerability Identification:** Mapping theoretical threats to concrete technical vulnerabilities.
- **Security Control Recommendations:** Aligning technical mitigations (e.g., parameterized queries, encryption) with business needs (e.g., PCI-DSS compliance).
- **Technical Documentation & Reporting:** Presenting complex security findings clearly and professionally.

---
