# Insurance Broker System – Manual Testing Project

This repository contains manual QA documentation for a **Demo Insurance Broker Web Application**. The project focuses on verifying the functionality and reliability of the quotation request, retrieval process, and user profile management modules.

## 🧾 Project Overview

- **Project Type:** Demo Web Application (Insurance Broker System)
- **Testing Type:** Manual Testing (UAT-focused)
- **Tested Modules:** Request Quotation, Retrieve Quotation, Profile
- **Tested By:** Usrah Saba
- **Duration:** [Month-Year]
- **Platform:** Web (Desktop)

## ✅ Objectives

- Validate core user functionalities such as quotation request and profile management
- Ensure data accuracy and input validation
- Detect and report bugs that impact user experience
- Perform both positive and negative test cases

## 🔍 Test Coverage Summary

| Module               | Tested Scenarios                         | Status     |
|----------------------|-------------------------------------------|------------|
| Quotation Request    | Form input, token generation              | ✅ Tested   |
| Retrieve Quotation   | Valid/Invalid quotation ID handling       | ✅ Tested   |
| User Profile         | View and Edit Information                 | ✅ Tested   |
| Input Validation     | Invalid data, empty fields, formatting    | ✅ Tested   |
| UI/UX Checks         | Layout, responsiveness, label consistency | ✅ Tested   |

## 📁 Repository Structure

insurance-broker-testing/
│
├── test-cases/
│ └── quotation-form-test-cases.xlsx
│
├── bug-reports/
│ └── insurance-bug-report.xlsx
│
├── screenshots/
│ ├── bug-profile-not-visible.png
│ ├── bug-edit-info-not-updated.png
│ └── bug-wrong-quote-token.png
│
└── README.md

pgsql
Copy
Edit

## 🐞 Key Bugs Identified

| Bug ID | Module             | Description                                                      | Severity | Status  |
|--------|--------------------|------------------------------------------------------------------|----------|---------|
| 001    | Profile             | User profile information not displaying after login              | Major    | Open    |
| 002    | Profile Edit        | Changes made in Edit Info section are not saved/shown           | Major    | Open    |
| 003    | Quotation Retrieval | System generates token even for invalid/wrong quotation ID       | Critical | Open    |

## 📸 Screenshots

**Bug 001 – Profile Not Showing**  
![Profile Bug](screenshots/bug-profile-not-visible.png)  
*Expected: User details should be visible after login. Actual: Blank profile section.*

**Bug 002 – Edit Info Not Saving**  
![Edit Info Bug](screenshots/bug-edit-info-not-updated.png)  
*Expected: Edited info should reflect in profile. Actual: No changes shown after saving.*

**Bug 003 – Invalid Quotation Still Generates Token**  
![Quotation Token Bug](screenshots/bug-wrong-quote-token.png)  
*Expected: Invalid quotation input should show error. Actual: Token generated regardless.*

## 📋 Deliverables

- ✅ Test Plan (basic)
- ✅ Test Cases (.xlsx)
- ✅ Bug Report (.xlsx)
- ✅ Screenshots
- ✅ Summary Report

## 👩‍💻 Author

**Usrah Saba**  
Manual QA Tester  
Email: usrahsaba18@gmail.com  
LinkedIn: [linkedin.com/in/usrah-saba](https://linkedin.com/in/usrah-saba)
