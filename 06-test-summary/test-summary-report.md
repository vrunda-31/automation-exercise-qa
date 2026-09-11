# Test Summary Report

## 1. Project Information

**Project:** Automation Exercise QA Portfolio  
**Application Under Test:** Automation Exercise  
**Testing Type:** Manual Functional Testing  
**Browser:** Google Chrome  
**Operating System:** Windows  
**Test Status:** Completed

---

## 2. Testing Objective

The objective of testing was to verify the major e-commerce functionalities of the application and identify defects that could affect the user experience.

The testing covered user registration, login, product browsing, product search, shopping cart, checkout, order placement, and logout.

---

## 3. Test Execution Summary

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

## 4. Module-wise Results

| Module | Executed | Passed | Failed |
|---|---:|---:|---:|
| Registration | 4 | 3 | 1 |
| Login | 6 | 6 | 0 |
| Products & Search | 5 | 5 | 0 |
| Shopping Cart | 6 | 6 | 0 |
| Checkout | 4 | 3 | 1 |
| Logout | 2 | 2 | 0 |
| **Total** | **27** | **25** | **2** |

---

## 5. Defect Summary

### BUG-001 — Invalid Email Format Accepted

**Module:** Registration  
**Severity:** Medium  
**Priority:** Medium  
**Status:** Open

The application accepted an invalid email format such as `test@gmailcom` during registration.

---

### BUG-002 — Invalid Payment Details Accepted

**Module:** Checkout / Payment  
**Severity:** High  
**Priority:** High  
**Status:** Open

The application accepted the invalid payment details entered during testing and successfully placed the order.

---

## 6. Key Findings

- Login functionality worked correctly for the tested scenarios.
- Product browsing and search functionality worked as expected.
- Shopping cart operations worked correctly for the tested scenarios.
- Two issues were identified during testing:
  - Invalid email format was accepted during registration.
  - Invalid payment details were accepted during order placement.
- The application successfully displayed an order confirmation after order placement.

---

## 7. Testing Conclusion

The major e-commerce workflows were successfully tested, and most executed test cases passed.

However, two defects were identified and remain open. Therefore, additional testing and defect verification would be recommended before considering the application fully ready for release.