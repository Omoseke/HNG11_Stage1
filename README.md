**Task**:


As a SysOps engineer, I have written a bash script called **create_users.sh** that reads a text file containing the new employee’s usernames and group names, where each line is formatted as user;groups.

The script would perform the following tasks:

Check if the script is run as root: Ensure the script has the necessary permissions to create users and groups.
Validate the input file: Ensure a filename is provided as an argument.
Define log and secure file paths: Set up paths for logging actions and securely storing passwords.
Create the log and secure files: Initialize the files for logging and password storage.
Log messages: By a defined function, it would append messages to the log file with timestamps.
Read the input file: Process each line in the file, creating users and groups as specified.
Generate random passwords: Create secure passwords for each user.
Set up home directories and permissions: Ensure each user has a secure home directory.
