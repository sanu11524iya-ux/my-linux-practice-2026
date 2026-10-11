# MY LINUX LEARNING DAY-03
*THESE ARE THE COMMANDS RELATED TO SECURITY AND CONTROL*
**grep "keyword"**: Searches and filters out specific keywords or patterns from a text file or large output.This command is used to find an error or a keyword from a file.
example-[Essential for troubleshooting; when an application crashes on an AWS EC2 instance, architects use it to instantly find errors within millions of lines of system logs (e.g., grep "ERROR" server.log)].
**|**(pipe operator): Chains two or more commands together by sending the output of the first command as the input to the next command.
example-[Used to combine active monitoring commands to check system health, such as listing all running services and filtering out the database status in one go (e.g., ps aux | grep mysql)].
**history**:list of all the previous commands executed in the current terminal session.
example-[ Critical for Cloud Security and Auditing; it allows system architects to track exactly what changes or configurations a team member made on a cloud server].
**chmod**:Modifies the read, write, and execute permissions of files and directories to manage security access.
example-[A fundamental AWS security requirement; whenever you download a Private Key (.pem file) to connect to a secure AWS EC2 instance, you must restrict its permissions using chmod 400 key.pem or AWS will reject the connection].
**sudo**:Give administrator/root level privileges to a normal user on that they make any changes on server.
example-[Used constantly on cloud infrastructure to perform high-level administrative tasks, such as installing packages, updating security patches, or restarting web servers (e.g., sudo systemctl restart nginx)].
