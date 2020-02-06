# Disk-Monitor-for-Windows
Powershell script to check available disk space on the servers in a text file

Use the script and run it on a schedule in windows task scheduler on your computer. Save it with .ps1 extension.

It does not use powershell remoting so it will work from Server 2008R2 till the latest available server OS (until microsoft does 
not depricate WMI).

Open the script and change the location for log files, threshold, server list and your email address.

Run it with domain privileged account so that you do not encounter permission issue.

If any servers are running low on storage space, it will also send you a pop up message.

Customize the messages as required in the script.



