# Bug Report: Missing "Forgot Password" Option on Login Page

---

## Bug ID:
UI-001

---

## Title:
Missing "Forgot Password" Option on Login Page

---

## Application:
Paylocity Benefits Dashboard

---

## Description:
The login page lacks the "Forgot Password" option, which is essential for users who need to recover their accounts. This omission may lead to a poor user experience, as users are unable to reset their password if they forget it.

---

## Steps to Reproduce:
1. Open the application URL: [Paylocity Login Page](https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login).
2. Observe the login page.
3. Note that the "Forgot Password" button is missing.

---

## Expected Result:
The login page should include a "Forgot Password" button that redirects users to a password recovery page.

---

## Actual Result:
No "Forgot Password" option is present on the login page, making it impossible for users to recover their password.

---

## Severity:
- **Major** (Critical if password recovery is mandatory).

---

## Environment:
- **OS**: macOS 15.1 (24B83)  
- **Browser**: Google Chrome Version 131.0.6778.265 (Official Build) (arm64)  
- **Device**: MacBook Pro M2 2022  

---

## Additional Details:
- **URL**: [Login Page](https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login)
- **Screenshots:**
  ![Login Page Missing Forgot Password](../screenshots/BUG-UI-001)
