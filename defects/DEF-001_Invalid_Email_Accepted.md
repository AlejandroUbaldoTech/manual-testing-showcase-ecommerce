# Account creation allows invalid email format

Environment
Browser: Chrome
Website: https://automationexercise.com

Steps to Reproduce
1. Navigate to signup page
2. Enter invalid email format (invalidemail@)
3. Complete the registration form
4. Submit the form

Expected Result
System should reject invalid email format and display validation error.

Actual Result
Account is successfully created despite invalid email format.

Severity
High

Priority
High

Impact
Invalid accounts can be created and users cannot recover passwords.
