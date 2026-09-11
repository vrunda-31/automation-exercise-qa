# Test Execution Log

## 1. Execution Information

**Project:** Automation Exercise QA Portfolio  
**Application Under Test:** Automation Exercise  
**Testing Type:** Manual Functional Testing  
**Browser:** Google Chrome  
**Operating System:** Windows  
**Execution Status:** Completed

---

## 2. Test Execution Summary

| Metric | Count |
|---|---:|
| Planned Test Cases | 29 |
| Executed Test Cases | 27 |
| Passed | 25 |
| Failed | 2 |
| Removed / Not Applicable | 2 |
| Pass Rate | 92.59% |

> Pass Rate = Passed Test Cases / Executed Test Cases × 100

---

## 3. Execution Results

### Registration

| Test Case | Result | Defect |
|---|---|---|
| TC-REG-01 | Pass | — |
| TC-REG-02 | Pass | — |
| TC-REG-03 | Pass | — |
| TC-REG-04 | Fail | BUG-001 |
| TC-REG-05 | Removed | — |

### Login

| Test Case | Result | Defect |
|---|---|---|
| TC-LOGIN-01 | Pass | — |
| TC-LOGIN-02 | Pass | — |
| TC-LOGIN-03 | Pass | — |
| TC-LOGIN-04 | Pass | — |
| TC-LOGIN-05 | Pass | — |
| TC-LOGIN-06 | Pass | — |

### Products & Search

| Test Case | Result | Defect |
|---|---|---|
| TC-PROD-01 | Pass | — |
| TC-PROD-02 | Pass | — |
| TC-PROD-03 | Pass | — |
| TC-PROD-04 | Pass | — |
| TC-PROD-05 | Pass | — |

### Shopping Cart

| Test Case | Result | Defect |
|---|---|---|
| TC-CART-01 | Pass | — |
| TC-CART-02 | Pass | — |
| TC-CART-03 | Pass | — |
| TC-CART-04 | Pass | — |
| TC-CART-05 | Pass | — |
| TC-CART-06 | Pass | — |

### Checkout

| Test Case | Result | Defect |
|---|---|---|
| TC-CHECKOUT-01 | Pass | — |
| TC-CHECKOUT-02 | Pass | — |
| TC-CHECKOUT-03 | Removed | — |
| TC-CHECKOUT-04 | Fail | BUG-002 |
| TC-CHECKOUT-05 | Pass | — |

### Logout

| Test Case | Result | Defect |
|---|---|---|
| TC-LOGOUT-01 | Pass | — |
| TC-LOGOUT-02 | Pass | — |

---

## 4. Failed Test Cases

### TC-REG-04

**Result:** Fail  
**Defect:** BUG-001

The application accepted an invalid email format such as `test@gmailcom` during registration.

---

### TC-CHECKOUT-04

**Result:** Fail  
**Defect:** BUG-002

The application accepted the invalid payment details entered during testing and successfully placed the order.

---

## 5. Removed Test Cases

### TC-REG-05

Removed because the application does not provide an account-details view that allows the registered information to be independently verified from the user interface.

### TC-CHECKOUT-03

Removed because the application uses the user's registered address/details during checkout instead of providing the separate checkout information form assumed by the original test case.

---

## 6. Overall Result

The major e-commerce user flows were successfully tested, including registration, login, product browsing, search, shopping cart, checkout, and logout.

Most executed test cases passed. Two defects were identified and documented as BUG-001 and BUG-002.

Further testing and defect resolution would be required before considering the application fully ready for release.