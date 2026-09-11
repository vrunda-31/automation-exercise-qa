# Test Plan

## 1. Document Information

**Project:** Automation Exercise QA Portfolio  
**Application Under Test:** Automation Exercise  
**Document Version:** 1.0  
**Testing Type:** Manual Testing

---

## 2. Objective

The objective of this test plan is to define the scope, approach, resources, and activities required to test the major functionalities of the Automation Exercise web application.

The main goal is to identify defects and verify that the application works according to the defined requirements.

---

## 3. Scope

### In Scope

The following functionalities will be tested:

- User Registration
- User Login
- Product Browsing
- Product Search
- Product Details
- Shopping Cart
- Cart Quantity
- Product Removal
- Checkout
- Order Placement
- User Logout

### Out of Scope

- Source code testing
- Server infrastructure testing
- Production monitoring
- Internal payment gateway processing
- Performance/load testing
- Security penetration testing
- Mobile application testing

---

## 4. Testing Types

The following testing types will be performed:

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

## 5. Test Approach

Testing will be performed manually by:

1. Understanding the defined requirements and acceptance criteria.
2. Creating test scenarios and detailed test cases.
3. Preparing suitable test data.
4. Executing test cases on the application.
5. Comparing actual results with expected results.
6. Reporting reproducible defects.
7. Retesting fixed defects.
8. Performing regression testing on related functionality.
9. Documenting final test results.

---

## 6. Test Environment

**Application:** Automation Exercise Web Application

**Browser:** Google Chrome

**Operating System:** Windows

**Testing Method:** Manual

**Tools:**
- Google Chrome
- Excel / Google Sheets
- Git / GitHub

---

## 7. Test Data

Test data will include:

- Valid user registration details
- Existing user credentials
- Invalid email addresses
- Incorrect passwords
- Product search terms
- Products for cart testing
- Checkout information

Test data will be created or selected specifically for testing and will not contain sensitive personal information.

---

## 8. Entry Criteria

Testing can begin when:

- The application is accessible.
- The required test environment is available.
- Requirements and acceptance criteria are defined.
- Test cases are prepared.
- Required test data is available.

---

## 9. Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed.
- Critical functionality has been tested.
- Identified defects have been documented.
- Fixed defects have been retested.
- Required regression testing has been completed.
- Test results have been documented.

---

## 10. Defect Management

Defects found during testing will be documented with:

- Defect ID
- Summary
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Environment
- Evidence such as screenshots

Defects will be retested after the fix is provided.

---

## 11. Risks and Assumptions

### Risks

- Application behavior may change during testing.
- Test environment or website availability may affect execution.
- Some external services may not be fully testable.

### Assumptions

- The application is available during testing.
- The defined requirements represent the expected behavior for this portfolio project.
- Testing will be performed using the available web application.