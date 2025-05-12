Hello! 😎

This is a simple console application built using VB.NET and MailKit .NET library that connects to your Gmail account via IMAP, scans last 50 emails for common spam keywords, and moves suspected spam emails to the junk folder. 

This app is based on a real-world spam filtering tool I developed for a client. They were using Google Workspace within a VB.NET legacy system.

---

Features:

- Secure IMAP connection to Gmail
- Scans subject lines for spam-related keywords
- Moves matching emails to the junk/spam folder
- Processes the 50 most recent emails
- Lightweight, easily extendable console application

---

Setup Instructions:

1. If you have admin privileges in your Google Workspace email system enable IMAP in your Gmail settings: https://mail.google.com/mail/u/0/#settings/fwdandpop 

2. Enable 2-Step Verification (if you haven't done so already): https://myaccount.google.com/security

3. Generate an app password: https://myaccount.google.com/apppasswords

4. Download or clone this repository

5. Open the solution in Visual Studio

6. Go to Tools -> NuGet Package Manager -> Manage NuGet Packages

7. Install MailKit package

Once inside the project:

1. Change the "your_email@gmail.com" variable to your email

2. Change the "your_password" variable to your password key, generated in Step 3

3. Change the spamKeywords values to what you need them to be

4. Press F5 or Ctrl + F5 in Visual Studio window to run

5. It will connect, scan the last 50 emails, and move spam to Junk 

Done!

Example output:
![Screenshot 2025-05-12 130809](https://github.com/user-attachments/assets/333ea830-6dbc-48fa-8068-25222547d344)
