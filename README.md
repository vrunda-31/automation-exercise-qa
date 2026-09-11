# Automation Exercise – QA Testing 

## Project Overview

This is a personal QA portfolio project created to demonstrate practical manual testing skills using the Automation Exercise e-commerce web application.

The project covers requirement analysis, test planning, test case design, test execution, defect reporting, and requirements traceability.

---

## Application Under Test

**Application:** Automation Exercise  
**Application Type:** E-commerce Web Application

**Website:** https://automationexercise.com/

---

## Project Objective

The objective of this project is to test the major e-commerce user flows and verify that the application behaves according to the defined requirements.

The project focuses on identifying functional defects and documenting the complete testing process.

---

## Modules Tested

The following modules were tested:

- User Registration
- User Login
- Product Browsing
- Product Search
- Shopping Cart
- Checkout
- Order Placement
- User Logout

---

## Testing Types

The project includes:

- Functional Testing
- Positive Testing
- Negative Testing
- Smoke Testing
- Sanity Testing
- Regression Testing
- Retesting
- Exploratory Testing
- Usability Testing
- Boundary Value Analysis
- Equivalence Partitioning

---

## Test Environment

| Item | Details |
|---|---|
| Application | Automation Exercise |
| Browser | Google Chrome |
| Operating System | Windows |
| Testing Approach | Manual Testing |

### Tools

- Google Chrome
- Excel / Google Sheets
- Git / GitHub

---

## Test Execution Summary

| Metric | Result |
|---|---:|
| Planned Test Cases | 29 |
| Executed Test Cases | 27 |
| Passed | 25 |
| Failed | 2 |
| Removed / Not Applicable | 2 |
| Pass Rate | 92.59% |
| Defects Identified | 2 |

---

## Defects Identified

### BUG-001 – Invalid Email Format Accepted

**Module:** Registration  
**Severity:** Medium  
**Priority:** Medium

The application accepted an invalid email format such as:

`test@gmailcom`

The expected behavior was to reject the invalid email format and display appropriate validation.

---

### BUG-002 – Invalid Payment Details Accepted

**Module:** Checkout / Payment  
**Severity:** High  
**Priority:** High

The application accepted the invalid payment details entered during testing and successfully placed the order.

This was documented as a defect based on the expected validation behavior defined for the test.

---

## Project Structure

```text
automation-exercise-qa/
│
├── README.md
│
├── 01-requirements-and-specifications/
│   ├── business-requirements-document.md
│   └── user-stories-and-acceptance-criteria.md
│
├── 02-test-strategy-and-planning/
│   ├── test-plan-v1.0.md
│   └── environment-and-scope-matrix.md
│
├── 03-test-design-and-execution/
│   ├── requirements-traceability-matrix.xlsx
│   ├── functional-test-cases.xlsx
│   └── test-execution-logs.md
│
├── 04-defect-reports/
│   └── bug-reports.md
│
├── 05-artifacts-and-evidence/
│   └── screenshots/
│
└── 06-test-summary/
    └── test-summary-report.md