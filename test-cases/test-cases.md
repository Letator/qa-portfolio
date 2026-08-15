Test Cases

This document contains examples of manual test cases for a web application.

The examples demonstrate positive, negative, validation, functional, and session-related testing scenarios.

---

Authentication

TC-001 — Login with valid credentials

Priority: High
Type: Functional / Positive

Preconditions:

- A registered user account exists.
- The user is on the login page.

Test Steps:

1. Enter a valid email address.
2. Enter a valid password.
3. Click the Login button.

Expected Result:

- The user is successfully authenticated.
- The user is redirected to the appropriate page.
- The user account information is displayed.

---

TC-002 — Login with invalid password

Priority: High
Type: Functional / Negative

Preconditions:

- A registered user account exists.
- The user is on the login page.

Test Steps:

1. Enter a valid email address.
2. Enter an incorrect password.
3. Click the Login button.

Expected Result:

- The user is not authenticated.
- An appropriate error message is displayed.
- The user remains on the login page.

---

TC-003 — Login with empty required fields

Priority: Medium
Type: Validation / Negative

Preconditions:

- The user is on the login page.

Test Steps:

1. Leave the email field empty.
2. Leave the password field empty.
3. Click the Login button.

Expected Result:

- The login request is not submitted.
- Validation messages are displayed for the required fields.
- The user remains on the login page.

---

TC-004 — Password visibility toggle

Priority: Low
Type: Functional / UI

Preconditions:

- The user is on the login page.
- The password field is available.

Test Steps:

1. Enter a password into the password field.
2. Click the password visibility icon.
3. Observe the password field.
4. Click the visibility icon again.

Expected Result:

- The password becomes visible after clicking the icon.
- The password is hidden again after clicking the icon a second time.
- The entered password value is not changed.

---

Password Recovery

TC-005 — Password reset with registered email

Priority: High
Type: Functional / Positive

Preconditions:

- A registered user account exists.
- The user is on the password recovery page.

Test Steps:

1. Enter the registered email address.
2. Click the Reset Password / Send button.
3. Check the user's email inbox.

Expected Result:

- The password reset request is accepted.
- A confirmation message is displayed.
- A password reset email is sent to the registered email address.
- The reset link allows the user to set a new password.

---

User Session

TC-006 — Logout from the application

Priority: High
Type: Functional / Session

Preconditions:

- The user is successfully logged in.

Test Steps:

1. Open the user account menu.
2. Click Logout.
3. Try to access a page that requires authentication.

Expected Result:

- The user is successfully logged out.
- The user is redirected to the login page or public page.
- Protected pages are no longer accessible without authentication.
