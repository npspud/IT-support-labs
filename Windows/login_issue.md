## Problem
User was unable to log into a local Windows account due to incorrect credentials.

## Environment
Windows system using a dual-boot setup with a local user account.

## Steps Taken
- Attempted to login and confirmed authentication failure
- Navigated to user account settings but no password reset option available
- Opened Command Prompt with administrative privileges
- Used 'net user' to verify account
- Used 'net user' command with the username to reset password
- Verified successful login with updated credentials

## Tools Used
- Windows Command Prompt
- net user command

## Outcome
Successfully restored access to the user account by resetting the password via command line and verifying login functionality.
