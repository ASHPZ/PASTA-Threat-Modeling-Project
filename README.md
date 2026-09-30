Sneaker Marketplace - PASTA Threat Model

Project Overview

This project is part of my portfolio developed during the Google Cybersecurity Professional Certificate. It showcases a practical application of threat modeling using the PASTA (Process for Attack Simulation and Threat Analysis) framework.

The scenario involves acting as a Cybersecurity Specialist for a sneaker enthusiast company preparing to launch a new mobile marketplace application. The goal is to analyze the application's architecture, identify potential threats and vulnerabilities, and recommend actionable security controls prior to deployment.

Methodology

The PASTA framework is a risk-centric threat modeling approach that consists of seven stages. I have documented the completion of each stage for the mobile application:

Define Business and Security Objectives: Identified core goals such as secure transactions, data privacy, and PCI-DSS compliance.

Define Technical Scope: Mapped out critical components, including APIs, SQL databases, and cryptographic protocols (SHA-256, AES).

Decompose Application: Analyzed data flow (DFD) between users, product search APIs, and the database.

Threat Analysis: Identified specific threats, notably SQL Injections and Session Hijacking.

Vulnerability Analysis: Pinpointed weaknesses such as the lack of prepared statements and weak login credentials.

Attack Modeling: Evaluated attack trees to understand the paths an attacker might take to compromise user data.

Risk Analysis & Impact: Proposed comprehensive mitigation strategies, including parameterized queries, Multi-Factor Authentication (MFA), and the Principle of Least Privilege.

Files Included

PASTA_Threat_Model_Report.pdf: The complete, finalized security report containing all seven stages of the analysis.

PASTA-data-flow-diagram.pptx: The provided architecture diagram.

PASTA-attack-tree.pptx: The provided attack tree diagram.

Skills Demonstrated

Threat Modeling & Risk Assessment

PASTA Framework Implementation

Vulnerability Identification

Security Control Recommendations

Technical Documentation & Reporting
