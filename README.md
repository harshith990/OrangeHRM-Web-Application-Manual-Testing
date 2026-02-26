# OrangeHRM Web Application – Manual Testing Project

## 📌 Project Overview
This project involves end-to-end manual testing of the **OrangeHRM Human Resource Management System**.
The goal was to validate core functional modules, design structured test artifacts, and ensure
the application meets quality standards before deployment.

🔗 **Application Under Test:** https://opensource-demo.orangehrmlive.com  
👤 **Role:** QA Tester  
🧪 **Testing Type:** Manual Testing

---

## 📂 Modules Tested

| # | Module | Test Cases | Scenarios |
|---|--------|------------|-----------|
| 1 | Login / Logout | 7 | 7 |
| 2 | Admin (User Mgmt, Job, Pay Grade, Shifts) | 12 | 12 |
| 3 | PIM – Employee Management | 16 | 16 |
| 4 | Recruitment | 8 | 10 |
| 5 | My Info – ESS (Employee Self Service) | 9 | 10 |
| 6 | Dashboard | 3 | 3 |
| **Total** | | **55** | **54** |

---

## 📋 Test Artifacts

| Artifact | Description |
|----------|-------------|
| `OrangeHRM_Test_Cases.xlsx` | Detailed test cases with steps, test data, expected vs actual results and status |
| `Test_Scenarios.xlsx` | High-level test scenarios mapped to Req# IDs |
| `Test_plan_doucment.pdf` | Test plan covering scope, approach, schedule, risks and entry/exit criteria |
| `Test_Summary_Report.pdf` | Summary of test execution with pass/fail metrics and conclusion |

---

## ✅ Test Execution Summary

| Metric | Value |
|--------|-------|
| Total Test Cases | 55 |
| Passed | 55 |
| Failed | 0 |
| Blocked | 0 |
| Pass Rate | 100% |

---

## 🛠️ Tools & Technologies

- **Test Management:** Microsoft Excel
- **Application:** OrangeHRM (Open Source Demo)
- **Browser:** Google Chrome, Mozilla Firefox
- **OS:** Windows 10 / 11
- **Document Creation:** Microsoft Word

---

## 🔍 Testing Approach

- **Methodology:** Manual Black-Box Testing
- **Techniques Used:** Equivalence Partitioning, Boundary Value Analysis, Error Guessing
- **Coverage:** Functional Testing, Smoke Testing, Regression Testing
- **Access Levels Tested:** Admin role and ESS (Employee Self Service) role

---

## 📁 Project Structure
```
OrangeHRM-Manual-Testing/
│
├── Test-Cases/
│   └── OrangeHRM_Test_Cases.xlsx
│
├── Test-Scenarios/
│   └── Test_Scenarios.xlsx
│
├── Test-Plan/
│   └── Test_plan_document.pdf
│
└── Test-Summary-Report/
    └── Test_Summary_Report.pdf
```

---

## 🎯 Key Highlights

- Designed and executed **55 test cases** across 6 functional modules
- Validated **role-based access control** — confirmed ESS users cannot edit Admin-restricted fields
- Verified complete **recruitment workflow** from vacancy creation to interview result marking
- Confirmed **session security** — browser back button does not allow access after logout
- Tested **data validations** including duplicate username prevention and mandatory field checks

---

## 👨‍💻 Author

**Harshith Dontha**  
📧harshithdontha@gmail.com 
🔗 [LinkedIn Profile]((https://www.linkedin.com/in/harshith-dontha-ba908a311/))
