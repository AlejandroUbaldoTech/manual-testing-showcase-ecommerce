# Account creation allows weak password

Environment
Browser: Chrome
Website: https://automationexercise.com

Steps to Reproduce
1. Navigate to https://automationexercise.com
2. Click the ""Signup / Login"" button
3. Enter a valid name and email address in the signup section
4. Click the ""Signup"" button
5. Complete the account registration form with the test data information
6. Submit the registration form

Test Data
Name: Test User
Email: testuser1234@examplegmail.com
Password: ab1
Address: 13 Mountain View Pl, Montclair, NJ 07042, USA
Date Of Birth: January 6th, 2021
Phone Number: (201) 874-8593

Expected Result
The system should display validation messages indicating that the password lenght must be at least 12 character and prevent account creation.

Actual Result
The user account was successfully created and the system displays a confirmation message indicating that the account has been created.

Severity
High

Priority
High

Impact
Customer account security is vulnerable which can lead to any person have access to their payment information and loss of their account and trust
