# TestCase_Gmail
Gmail testing includes verifying login, email sending/receiving, attachments, and spam filtering. It ensures smooth functionality across devices.
Login Functionality

Test Case: Verify that users can log in with valid credentials.

Steps: Enter the correct email and password, then click "Sign In."

Expected Result: The user should successfully log in and reach the inbox.

Invalid Login Attempt

Test Case: Check login with incorrect credentials.

Steps: Enter an incorrect email or password and try to log in.

Expected Result: An error message should be displayed, preventing login.

Forgot Password Functionality

Test Case: Ensure users can reset their password if forgotten.

Steps: Click on "Forgot Password," enter the email, and follow the reset steps.

Expected Result: A password reset email should be sent to the registered email.

Compose & Send Email

Test Case: Verify that users can compose and send emails.

Steps: Click "Compose," enter recipient details, add a subject and body, then click "Send."

Expected Result: The email should be sent successfully, and the recipient should receive it.

Receiving Emails

Test Case: Ensure emails sent to the account are received.

Steps: Send an email from another account and check the inbox.

Expected Result: The email should appear in the inbox.

Email Attachments

Test Case: Verify users can attach files to an email.

Steps: Click "Compose," attach a file, and send the email.

Expected Result: The recipient should receive the email with the attachment.

Email Forwarding

Test Case: Ensure users can forward received emails.

Steps: Open an email, click "Forward," enter recipient details, and send.

Expected Result: The email should be forwarded successfully.

Reply to Email

Test Case: Check that users can reply to an email.

Steps: Open an email, click "Reply," type a response, and send.

Expected Result: The reply should be sent to the sender.

Email Deletion

Test Case: Verify that users can delete emails.

Steps: Select an email and click "Delete."

Expected Result: The email should move to the Trash folder.

Spam Filtering

Test Case: Ensure spam emails are detected and filtered.

Steps: Send a suspicious email to the test account and check the Spam folder.

Expected Result: The email should be categorized under Spam.

Search Functionality

Test Case: Verify users can search for emails using keywords.

Steps: Type a keyword in the search bar and press enter.

Expected Result: Relevant emails should be displayed in the search results.

Logout Functionality

Test Case: Ensure users can log out securely.

Steps: Click on the profile icon and select "Sign out."

Expected Result: The user should be logged out and redirected to the login page.

Draft Saving Feature

Test Case: Check if Gmail saves draft emails automatically.

Steps: Start composing an email and close the window without sending.

Expected Result: The email should be saved in the Drafts folder.

Two-Factor Authentication

Test Case: Verify that 2FA works correctly for security.

Steps: Enable 2FA, log in, and enter the OTP sent to the registered mobile number.

Expected Result: The user should log in only after entering the correct OTP.

Multiple Account Switching

Test Case: Ensure users can switch between multiple Gmail accounts.

Steps: Add multiple accounts, click on the profile icon, and select another account.

Expected Result: The selected account should open without logging out.

Session Expiry Handling

Test Case: Check how Gmail handles inactive sessions.

Steps: Log in and remain inactive for an extended period.

Expected Result: The session should expire, and Gmail should prompt for re-login.

Gmail Mobile App Compatibility

Test Case: Verify that Gmail functions correctly on mobile devices.

Steps: Open Gmail on an Android/iOS app and perform actions like login, sending emails, and searching.

Expected Result: All functions should work smoothly on the mobile app.

Email Scheduling

Test Case: Check if Gmail allows scheduling an email to be sent later.

Steps: Click "Compose," select "Schedule Send," and choose a future time.

Expected Result: The email should be sent at the scheduled time.

Notifications on New Emails

Test Case: Ensure users receive notifications for new emails.

Steps: Enable email notifications and send an email to the test account.

Expected Result: A notification should appear when the email arrives.

Undo Send Feature

Test Case: Verify users can undo an email sent by mistake.

Steps: Send an email and immediately click "Undo" before the time limit expires.

Expected Result: The email should not be sent and should return to drafts.
