# Jamf Zero Touch - Jamf Setup Manager at Stanford University
Stanford University's implementation of Jamf Setup Manager in macOS device enrollment.

## What does Jamf Setup Manager do?
This is an baseline app and configuration application
* invoked during Setup Assistant and automated device enrollment in Jamf
* with progress indicators and customization options like Stanford branding
* expediting the Mac setup process by ensuring core applications are installed even before one logs in to Mac for the first time

For more information, see the "What it does" section of the authors' Github repository here: https://github.com/Jamf-Concepts/Setup-Manager/tree/main

## Feature and Enhancement Ideas
- Allow user re-assignment to:
  * intake username as the input, with the "User Email" field renamed accordingly
  * update the device record's username field accordingly -- leaving email address untouched (unless specified otherwise)
- Make "Submit User Entry" and "install_extra_apps" action conditionally show only when using "Conditionally show the user entry for certain users" workflow
