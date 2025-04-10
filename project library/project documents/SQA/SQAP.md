# Software Quality Assurance Plan

## Title Page

**Software Quality Assurance Plan**  
**FitChat – Fitness Messaging App**  
Prepared By: Software Solutions  
Prepared For: BIGmuscles Inc.  
Approved By: Prof. Wood  
Author: Cooper Snesko

---

## Revision History

| Version | Date       | Author          | Changes Made        |
|---------|------------|------------------|---------------------|
| 0.1.0   | 2025-04-07 | Cooper Snesko    | Initial draft       |


---

## Table of Contents

Section                                Page  
1 - Overview                           1  
2 - References and Acronyms           2  
3 - Referenced Documents               3  
  3.1 - Contract Reference              3  
4 - Management                         4  
5 - Documentation                      5  
6 - Standards, Practices, Conventions, and Metrics  6  
7 - Reviews and Audits                 7  
8 - Test                               8  
9 - Problem Reporting and Corrective Action  9  
10 - Tools, Techniques, and Methodologies  10  
11 - Code Control                      11  
12 - Media Control                     12  
13 - Supplier Control                  13  
14 - Records Collection, Maintenance, and Retention  14  
15 - Training                          15  
16 - Risk Management                   16  
17 - Glossary                          17  

---

## Table of Figures

 This section will be updated in future versions.

---

## 1. Overview

### 1.1 Purpose
This document defines the Software Quality Assurance Plan (SQAP) for the *FitChat* application. Its purpose is to describe the quality assurance activities to be implemented to ensure that the software product meets or exceeds specified requirements and expectations.

### 1.2 Scope
FitChat is a mobile application designed to send real time fitness based messages between users. Features include private and group messaging, sharing workout stats, and integration with popular fitness trackers such as nike run anod others. The project scope includes initial development and app for Android and iOS.

### 1.3 References to CONOPS and Contract
This SQAP references the Concept of Operations (CONOPS) for FitChat version 1.0, which defines the user workflow and system goals. The project is under Contract with BIGmuscles Inc.

---

## 2. References and Acronyms

- **SQA** – Software Quality Assurance: Activities ensuring a software product meets the specified requirements and standards.
- **CONOPS** – Concept of Operations: A document describing how the system will be operated to meet user needs.
- **CI/CD** – Continuous Integration / Continuous Deployment: A software development practice of frequent integration and automated deployment.

---

## 3. Referenced Documents

- Contract with BIGmuscles Inc.  
- IEEE 730-2014 - IEEE Standard for Software Quality Assurance Processes  
- This SQAP document stored in the CM Library GitHub repository  

### 3.1 Contract Reference  
Refer to Contract with BIGmuscles Inc.  

---

## 4. Management  
The FitChat project is managed by Software Solutions. The QA Manager is responsible for ensuring QA activities are performed. Regular status meetings will be held weekly to review progress and issues.

---

## 5. Documentation  
Key documents include the CONOPS, SQAP, design specs, test plans, and user manuals. All documents are stored in the GitHub CM Library and updated with each project milestone.

---

## 6. Standards, Practices, Conventions, and Metrics  
We follow IEEE 730-2014 standards. Coding conventions are based on common mobile development best practices. Metrics include defect density and test coverage.

---

## 7. Reviews and Audits  
Code and document reviews occur at each milestone. Formal audits may be performed by the QA team or project stakeholders.

---

## 8. Test  
Testing includes unit, integration, and system testing. Test cases are created from requirements. Both manual and automated testing will be used.

---

## 9. Problem Reporting and Corrective Action  
Issues are tracked using GitHub Issues. Developers fix bugs and QA re-tests before closing. Major issues are discussed in team meetings.

---

## 10. Tools, Techniques, and Methodologies  
We use GitHub for version control and issue tracking. Testing tools may include JUnit (Android) and XCTest (iOS). Agile methodology is followed with 2-week sprints.

---

## 11. Code Control  
All code is stored in a private GitHub repository. Changes require pull requests and approvals. Version tags are used for releases.

---

## 12. Media Control  
Media files (images, icons) are stored in a centralized folder within the project repo. Only the design team may update them.

---

## 13. Supplier Control  
We do not use external software suppliers. All work is performed by the internal team at Software Solutions.

---

## 14. Records Collection, Maintenance, and Retention  
Project records are stored in GitHub and backed up regularly. Documents are retained for the life of the product.

---

## 15. Training  
Team members are trained on project tools, development practices, and QA procedures during onboarding and as needed.

---

## 16. Risk Management  
Risks are identified during planning and reviewed in meetings. Common risks include app crashes, data syncing issues, and user privacy concerns. Mitigation includes testing, code reviews, and secure design.

---

## 17. Glossary  
- **QA** – Quality Assurance  
- **CM** – Configuration Management  
- **UI** – User Interface  
- **API** – Application Programming Interface  
- **GitHub** – A platform for version control and collaboration  

---

## Configuration Infrastructure

### Part 1: Identified Configuration Items (CIs) from CMM Activities

**CMM Level 2**  
*Key Process Areas: Software Project Planning, Software Quality Assurance*  
1. Project schedule  
2. Cost estimate  
3. Staffing plan  
4. Risk management plan  
5. Quality Assurance Plan  
6. Audit results  
7. SQA plan compliance report  
8. Meeting notes from planning review  
9. Requirements traceability matrix  
10. Review checklist

**CMM Level 3**  
*Key Process Areas: Peer Reviews, Organization Process Focus*  
11. Peer review reports  
12. Training materials  
13. Organization standard procedures  
14. Process improvement proposals  
15. Internal audit checklists

**CMM Level 4**  
*Key Process Areas: Software Quality Management, Quantitative Process Management*  
16. Quality metrics reports  
17. Process capability baselines  
18. Data analysis results  
19. Quality goal tracking reports  
20. Software defect metrics report

**CMM Level 5**  
*Key Process Areas: Defect Prevention, Process Change Management*  
21. Causal analysis meeting minutes  
22. Defect prevention plans  
23. Action proposals from defect meetings  
24. Defect trend charts  
25. Process revision logs

**Additional from other levels to reach 30 total**  
26. Version control logs  
27. Integration test summary  
28. Unit test reports  
29. Configuration management meeting notes  
30. Software release notes

---

### Part 2: Categorized Configuration Items

**Project Library**
- *Program Management*:  
  - Program Management Plan  
  - Project Management Budget  
  - Weekly project status meetings  
  - Project Management: Cause, Analysis, and Resolution  
  - Program Management Schedule  
- *System Engineering*:  
  - Software Requirements Specification  
  - Architecture Design Document  
  - Rough order of magnitude  
- *Configuration Management*:  
  - Configuration Management Process (all listed variations)  
  - Configuration Management Policies  
  - Version Description Document  
  - Weekly planning meetings  
- *Software Development*:  
  - Software Development Plan  
  - Development plan for Module B  
  - Software Development Reviews of Unit A.1-A.6  
  - Software Development Reviews of Unit B.1-B.7  
  - Software Development Review checklist  
- *Software Testing*:  
  - Software Testing Plan  
  - Test Case checklists  
  - System Test Cases  
  - Acceptance Test Cases  
  - Software Testing Process (Update)  
- *Quality Assurance*:  
  - Quality Assurance Plan  
  - Peer review reports  
  - Audit reports  

**Software Library**
- *Source Code*:  
  - Main app source files  
- *Test Code*:  
  - Unit Test for Module A  
- *Test Data*:  
  - Input/output data for test cases  
- *Test Scripts*:  
  - Nightly automated test scripts  
- *Delivery Scripts*:  
  - Compile scripts  
  - Version build script  
- *Configuration Scripts*:  
  - Scripts to build new SW work product  
- *3partylibrary*:  
  - 3-Party library compiled code  
- *3partySourceCode*:  
  - Source code (if available) from 3rd party  
- *Deliveries*:  
  - Delivery package for Mobile App  
  - Delivery package for Windows App  
  - Delivery package for Web Server  
  - Delivery package for Web Client  
  - Delivery package for iOS App  
  - Delivery package for Linux App  

---

### Part 3: Organized Library Infrastructure

**Project Library**
- /project_library/  
  ├── program_management/  
  ├── system_engineering/  
  ├── configuration_management/  
  ├── software_development/  
  ├── software_testing/  
  └── quality_assurance/  

**Software Library**
- /software_library/  
  ├── source_code/  
  ├── test_code/  
  ├── test_data/  
  ├── test_scripts/  
  ├── delivery_scripts/  
  ├── configuration_scripts/  
  ├── 3partylibrary/  
  ├── 3partySourceCode/  
  └── deliveries/
