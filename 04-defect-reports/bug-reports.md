# Bug Reports

## BUG-001 — Invalid Email Format Accepted During Registration

### Bug Information

**Bug ID:** BUG-001  
**Related Test Case:** TC-REG-04  
**Module:** User Registration  
**Severity:** Medium  
**Priority:** Medium  
**Status:** Open  
**Environment:** Automation Exercise, Google Chrome, Windows

### Summary

The registration form accepts an invalid email address format such as `test@gmailcom`.

### Preconditions

- User is on the Signup / Login page.
- User is attempting to create a new account.

### Steps to Reproduce

1. Open the Automation Exercise website.
2. Navigate to **Signup / Login**.
3. Enter a valid name.
4. Enter an invalid email address such as `test@gmailcom`.
5. Click **Signup**.
6. Complete the remaining required registration details.
7. Click **Create Account**.

### Expected Result

The system should validate the email format and prevent registration when an invalid email address is entered.

### Actual Result

The system accepts `test@gmailcom` and allows the user to continue with registration.

### Evidence

Screenshot showing successful registration with the invalid email format.

### Impact

Users can create accounts using incorrectly formatted email addresses, which may cause problems with account communication or email-based functionality.

---

## BUG-002 — Invalid Payment Details Accepted During Order Placement

### Bug Information

**Bug ID:** BUG-002  
**Related Test Case:** TC-CHECKOUT-04  
**Module:** Checkout / Payment  
**Severity:** High  
**Priority:** High  
**Status:** Open  
**Environment:** Automation Exercise, Google Chrome, Windows

### Summary

The application allows an order to be placed even when invalid payment details are entered.

### Preconditions

- User is logged in.
- User has at least one product in the cart.
- User has proceeded to the checkout page.

### Steps to Reproduce

1. Add a product to the cart.
2. Proceed to checkout.
3. Review the order details.
4. Enter invalid/fake payment information.
5. Enter an invalid card number.
6. Enter an invalid CVV.
7. Enter an invalid expiry date.
8. Click **Pay and Confirm Order**.

### Expected Result

The system should validate the payment details and prevent the order from being placed when invalid payment information is entered.

### Actual Result

The application accepts the entered payment details and successfully places the order.

The application displays:

**"ORDER PLACED!"**

and:

**"Congratulations! Your order has been confirmed!"**

### Evidence

Screenshot of the order confirmation page after entering invalid payment details.

### Impact

The application appears to accept invalid payment information and complete an order, which could indicate missing payment validation.

---

## Defect Summary

| Bug ID | Module | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-001 | Registration | Medium | Medium | Open |
| BUG-002 | Checkout / Payment | High | High | Open |