# 🛒 OpenCart Manual Testing Project

## 📖 About This Project
Hi there! 👋  
This is my **end-to-end manual testing project** on the **OpenCart** e-commerce application (version 4.1.0.3).  
The goal was to simulate a real-world QA process — starting from requirement gathering, through detailed test design and execution, and ending with bug reporting and test closure.

I worked on this project as if I were part of a professional QA team:
- Documented requirements into an **FRS (Functional Requirement Specification)**.
- Created a **Test Plan** covering scope, strategy, and timelines.
- Designed **100+ test cases** for different functional areas.
- Executed all tests on a local OpenCart setup deployed using **XAMPP**.
- Reported bugs with proper screenshots and severity levels.
- Managed the Agile workflow entirely in **Jira with Zephyr**.

This project shows my ability to handle **real-world QA responsibilities** from scratch to sign-off.

---

## 📂 Repository Structure

```plaintext
OpencartManualTestProj/
│
├── FRS AND TEST PLAN AND DEPLOYMENT/
│   ├── BUILDDEPLOY MANUAL.pdf              # Local deployment guide
│   ├── OpenCart -FRS.pdf                   # Functional Requirement Specification
│   ├── OpenCart -Test Plan.pdf              # Test planning document
│
├── TEST SCENARIO AND TESTCASES/
│   ├── TestScenario&casesOpencart.xlsx      # All designed test cases & scenarios
│
├── TEST RESULT/
│   ├── Bug Screenshots/                     # Screenshots for each failed test case
│   ├── TestScenario&casesOpencart-results 1.xlsx  # Execution result sheet
│
├── jiraTest/
│   ├── jira reports/                        # Zephyr reports exported from Jira
│       ├── Zephyr - Jira detailed report.pdf
│       ├── Zephyr - Jira summary list.pdf
│       ├── Zephyr - Jira scorecard execution tester.pdf
│       ├── Zephyr - Jira-Test execution.pdf
│       ├── Zephyr - Jira-Tracability testcase.pdf
│       ├── Zephyr - Jira-executionscorecard.pdf
│
├── opencart-4.1.0.3.zip                      # Application package for local setup
└── README.md                                 # Project documentation (this file)
```
Note: Large Jira activity recordings are stored separately in Google Drive to keep the repository size manageable.
---

## 🛠 Tools & Technologies Used
- **Application Under Test:** OpenCart 4.1.0.3
- **Deployment Environment:** XAMPP (Localhost)
- **Test Management:** Jira with Zephyr plugin
- **Documentation Tools:** Microsoft Excel, Word, PDF
- **Evidence:** Annotated screenshots for bugs
- **Process:** Agile Scrum

---

## 📌 My Testing Workflow

1. **Requirement Analysis**
   - Read and understood the OpenCart features.
   - Documented them in a clear **Functional Requirement Specification (FRS)**.

2. **Test Planning**
   - Prepared a **Test Plan** with:
     - Testing objectives and scope
     - Required resources
     - Entry/Exit criteria
     - Timelines and responsibilities

3. **Test Design**
   - Designed 100+ functional, negative, and UI test cases.
   - Maintained traceability between requirements and test cases (RTM).

4. **Test Execution**
   - Set up OpenCart locally using XAMPP.
   - Ran all test cases.
   - Recorded **Pass/Fail** status in Excel.
   - Took detailed bug screenshots for failed test cases.

5. **Defect Reporting**
   - Reported each defect in Jira.
   - Added reproduction steps, severity, and evidence.

6. **Agile Workflow in Jira**
   - Created Epic → Backlog → User Stories → Sprint.
   - Linked test cases to Jira tasks.
   - Executed tests via Zephyr and tracked progress.
   - Generated Zephyr execution and traceability reports.

---

## 🎥 Jira Execution Recordings

To avoid large file uploads, all Jira recording videos are stored in Google Drive:  
📂 **[View Jira Test Recordings](https://drive.google.com/drive/folders/1lvti0TgxnHj_1uxQqshtTk5vEHEFlrkL?usp=drive_linkthis)**  

These recordings include:
- Jira project creation & Scrum board setup
- Epic and user story creation
- Test case creation in Zephyr
- Test cycle execution
- Sprint execution and bug updates
- Sprint closure and test sign-off

---

## 📊 Sample Reports from Jira

| Report Type                  | What It Shows                                  |
|------------------------------|-----------------------------------------------|
| **Detailed Report**          | Execution status for each test case           |
| **Summary List**             | Overall execution summary                     |
| **Execution Scorecard**      | Pass/Fail percentage and test health          |
| **Traceability Report**      | Requirement-to-test case mapping              |

---

## 📌 Key Stats & Highlights
- **Total Test Cases:** 100+
- **Failed Test Cases (Bugs Found):** 57
- **Bug Severity Distribution:** High, Medium, Low
- **Process Followed:** Complete Agile Scrum cycle
- **Full Documentation:** FRS, Test Plan, Test Cases, Execution Reports, Bug Evidence

---
### 🚀 How to Use This Project
1. Download `opencart-4.1.0.3.zip` and deploy it locally via XAMPP.
2. Refer to **BUILDDEPLOY MANUAL.pdf** for setup instructions.
3. Use the **FRS** and **Test Plan** to understand scope and requirements.
4. Check **Test Scenarios & Test Cases** for designed tests.
5. Review **Test Results** and **Bug Screenshots** for execution evidence.
6. Watch **Google Drive recordings** to see Jira execution in action.

---
