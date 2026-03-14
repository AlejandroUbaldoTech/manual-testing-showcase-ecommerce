# Account creation allows invalid email format

Environment
Browser: Chrome
Website: https://automationexercise.com

Steps to Reproduce
1. Navigate to https://automationexercise.com
2. Click the ""Signup / Login"" button
3. Enter a valid name and email address in the signup section
4. Click the ""Signup"" button
5. Complete the account registration form with the test data
6. Submit the registration form

Test Data
Name: @@@###
Email: testuser12345@examplegmail.com
Password: ValidPassword123
Address:13 Mountain View Pl, Montclair, NJ 07042, USA
Date Of Birth: January 6th, 2021
Phone Number: (201) 874-8593

Expected Result:
<p>
The system should display validation messages indicating that the user name contain special characters and prevent account creation.
<p>
Actual Result:
<p></p>
The user account was successfully created and the system displays a confirmation message indicating that the account has been created.<p></p>
Severity: Medium

Priority: Medium

Impact
Being able to create an account with special characters on the name can lead to issues when processing the payment during checkouts and delay order placing due to extra steps to correct it
