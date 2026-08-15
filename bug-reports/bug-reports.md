# Bug Reports

This document contains examples of bug reports for a web application.

The examples demonstrate how functional and usability issues can be documented clearly and consistently.

---

## BUG-001 — Login button remains disabled with valid credentials

**Severity:** Major  
**Priority:** High  
**Type:** Functional

**Environment:**
- Windows 11
- Google Chrome 139
- Web application

**Preconditions:**
- A registered user account exists.
- The user is on the login page.

**Steps to Reproduce:**
1. Enter a valid email address.
2. Enter a valid password.
3. Observe the **Login** button.

**Expected Result:**
The **Login** button becomes enabled and the user can submit the login form.

**Actual Result:**
The **Login** button remains disabled even though valid credentials have been entered.

---

## BUG-002 — Incorrect validation message for invalid email

**Severity:** Minor  
**Priority:** Medium  
**Type:** Validation / UI

**Environment:**
- Windows 11
- Google Chrome 139
- Web application

**Preconditions:**
- The user is on the registration page.

**Steps to Reproduce:**
1. Enter `userexample.com` into the email field.
2. Move focus to another field.
3. Observe the validation message.

**Expected Result:**
The application displays a clear message indicating that the email address format is invalid.

**Actual Result:**
The application displays the message `Invalid password`, although the password field has not been entered.

---

## BUG-003 — Password reset link redirects to an error page

**Severity:** Critical  
**Priority:** High  
**Type:** Functional

**Environment:**
- Windows 11
- Google Chrome 139
- Web application

**Preconditions:**
- A registered user account exists.
- The user can access the registered email account.

**Steps to Reproduce:**
1. Open the password recovery page.
2. Enter a registered email address.
3. Request a password reset link.
4. Open the received email.
5. Click the password reset link.

**Expected Result:**
The password reset page opens and allows the user to create a new password.

**Actual Result:**
The password reset link redirects the user to an error page.

---

## BUG-004 — Removed product remains in the shopping cart

**Severity:** Major  
**Priority:** High  
**Type:** Functional

**Environment:**
- Windows 11
- Google Chrome 139
- E-commerce web application

**Preconditions:**
- The user is logged in.
- At least one product is added to the shopping cart.

**Steps to Reproduce:**
1. Open the shopping cart.
2. Click **Remove** for a product.
3. Refresh the page.
4. Observe the shopping cart.

**Expected Result:**
The removed product is no longer displayed in the shopping cart.

**Actual Result:**
The removed product appears in the shopping cart again after the page is refreshed.

---

## BUG-005 — User session remains active after logout

**Severity:** Critical  
**Priority:** High  
**Type:** Security / Session

**Environment:**
- Windows 11
- Google Chrome 139
- Web application

**Preconditions:**
- The user is successfully logged in.

**Steps to Reproduce:**
1. Open a page that requires authentication.
2. Click **Logout**.
3. Use the browser Back button.
4. Try to access the previously opened protected page.

**Expected Result:**
The user is logged out and cannot access protected pages without logging in again.

**Actual Result:**
The previously opened protected page remains accessible after logout.

---

## Notes

These examples are fictional and are intended to demonstrate bug reporting structure and QA documentation practices.
