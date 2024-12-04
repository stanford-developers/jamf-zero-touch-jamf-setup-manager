# Jamf Zero Touch - Jamf Setup Manager at Stanford University
Stanford University's implementation of Jamf Setup Manager in macOS device enrollment.

## Feature and Enhancement Ideas
- Allow user re-assignment to:
  intake username as the input, with the "User Email" field renamed accordingly
  update the device record's username field accordingly -- leaving email address untouched (unless specified otherwise)
- Make "Submit User Entry" and "install_extra_apps" action conditionally show only when using "Conditionally show the user entry for certain users" workflow
  alternatively: create a toggle to hide these items and put them behind a "Finishing up..." stage
