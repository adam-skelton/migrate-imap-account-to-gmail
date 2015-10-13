Changes
-----
- Removed configurable folder so all emails are copied to respective folders at the root of the destination account. Emails are merged straight away into folders account if they already exist (automatically labelled in the case of Gmail)

- Removed user input confirmation at start of script for quick reruns in case of issues

- Added quick exception handling to skip emails and continue running if an error is encounered during processing.

- Added time stamps to log

- Log is output to the console and to a file on disk in the root of the script

- Small tweak to Imap client call to get it to work with Python 2.7

