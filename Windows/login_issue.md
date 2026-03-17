## Problem
User was unable to log into a local Windows account due to incorrect credentials.

## Environment
Windows system using a dual-boot setup with a local user account.

## Steps Taken
- Attempted to login and confirmed authentication failure
- Navigated to user account settings but no password reset option available
  
![No Gui Reset Available](IT-support-labs/Windows/images/login-issue/No_gui_reset.png

- Opened Command Prompt with administrative privileges
- Used 'net user' to verify account
  
![List Users](IT-support-labs/Windows/images/login-issue/User_search.png

- Used 'net user' command with the username to reset password

![Password Reset](IT-support-labs/Windows/images/login-issue/Password_reset.png

- Verified successful login with updated credentials

## Tools Used
- Windows Command Prompt
- net user command

## Outcome
Successfully restored access to the user account by resetting the password via command line and verifying login functionality.
