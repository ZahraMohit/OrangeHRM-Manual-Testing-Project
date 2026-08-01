# OrangeHRM Manual Testing Project

Manual QA testing project performed on the [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/) application, covering the full manual test cycle: planning, scenario design, test case execution, defect reporting, and final results reporting.

This project was built to demonstrate practical QA skills — planning, test design, execution discipline, and clear documentation — using a real, publicly available demo application.

## 📌 Project Overview

| Item              | Details                        |
|-------------------|---------------------------------|
| Application Under Test | OrangeHRM Demo             |
| Testing Type      | Manual Testing                  |
| Test Cycle        | Cycle 1                         |
| Modules Covered   | Login, User Management, My Info |
| Total Test Cases  | 35                               |
| Pass Rate         | 94.3% (33 Passed / 2 Failed)    |
| Browser           | Google Chrome                   |
| Operating System  | Ubuntu 24.04 LTS                |

## 🎯 Objectives

- Verify the functionality of core application features
- Validate user input fields and form validations
- Execute positive, negative, boundary value, and exploratory test scenarios
- Identify and document software defects
- Produce professional QA documentation following the STLC (Software Testing Life Cycle)

## 🧩 Scope

**In Scope:** Login, Logout, User Management (Add/Edit/Delete/Search User), My Info

**Out of Scope:** Performance, Load, Stress, API, Mobile, Automation, and Security Penetration Testing

## 📂 Deliverables

| # | Document | Description |
|---|----------|-------------|
| 1 | [`Test_Plan.xlsx`](./Test_Plan.xlsx) | Test strategy, scope, environment, entry/exit criteria, and risks |
| 2 | [`Test_Scenarios.xlsx`](./Test_Scenarios.xlsx) | 10 high-level test scenarios across all in-scope modules |
| 3 | [`Test_Cases.xlsx`](./Test_Cases.xlsx) | 35 detailed test cases with steps, test data, and expected/actual results |
| 4 | [`Bug_Reports.xlsx`](./Bug_Reports.xlsx) | 3 documented defects found during execution |
| 5 | [`Test_Execution_Report.xlsx`](./Test_Execution_Report.xlsx) | Final execution summary, module-wise breakdown, and conclusion |

> File names above assume you upload each workbook to the repo root using these names — rename to match if you use different filenames.

## ✅ Test Execution Summary

| Module           | Total | Passed | Failed | Pass Rate |
|-------------------|:-----:|:------:|:------:|:---------:|
| Login              | 12    | 12     | 0      | 100%      |
| User Management    | 12    | 11     | 1      | 91.7%     |
| My Info            | 9     | 8      | 1      | 88.9%     |
| Exploratory        | 2     | 2      | 0      | 100%      |
| **Total**          | **35**| **33** | **2**  | **94.3%** |

## 🐞 Key Defects Found

| Bug ID  | Title                                              | Severity | Priority | Status |
|---------|-----------------------------------------------------|----------|----------|--------|
| BUG_001 | System accepts future birth date                    | Medium   | High     | Open   |
| BUG_002 | System accepts unrealistic birth year (e.g. 1247)    | Medium   | Medium   | Open   |
| BUG_003 | Shared demo environment causes inconsistent test data (environment issue) | Low | Low | Open |

Full details, steps to reproduce, and expected/actual results are available in [`Bug_Reports.xlsx`](./Bug_Reports.xlsx).

## 🛠️ Tools Used

- **OrangeHRM Demo** — Application Under Test
- **Microsoft Excel** — Test documentation (Test Plan, Scenarios, Cases, Bug Reports, Execution Report)
- **Manual Testing Techniques** — Functional, Validation, Boundary Value, Negative, and Exploratory Testing

## 📖 How to Use This Repository

1. Start with `Test_Plan.xlsx` for the overall strategy and scope.
2. Review `Test_Scenarios.xlsx` for the high-level test coverage.
3. Open `Test_Cases.xlsx` for detailed step-by-step test cases and their results.
4. Check `Bug_Reports.xlsx` for the defects found during execution.
5. See `Test_Execution_Report.xlsx` for the final summary and conclusion.

## 👩‍💻 About the Author

**Zahra Mohit**
QA Engineer | Background in Physics & Cosmology

- GitHub: [github.com/ZahraMohit](https://github.com/ZahraMohit)
- LinkedIn: [linkedin.com/in/zahramohit](https://linkedin.com/in/zahramohit)

---

*This project was created as a portfolio piece to demonstrate manual QA testing skills, including test planning, test case design, defect reporting, and structured documentation aligned with real-world QA practices.*
