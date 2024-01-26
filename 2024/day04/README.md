##   Day 4 Started with Advanced Linux (Part -3) (End of Session)

## User Management Commands

   - who - Show who is currently logged in
   - sudo add user name - Create a new user account on the system with the specified user
   - finger - Display information of all the users currently logged into the system, 
   - sudo deluser USER GROUPNAME - Remove the specified user form the Specified group
   - last - Show the recent specified login history of users
   - finger username - Provide information about the specified user, including their username,re
   - sudo userdel -r username - Delete the specified user account from the system, including their home directory and associated files. The -r option ensures the removal of the user’s files.
   - sudo passwd -l username - Lock the password of the specified user account, preventing the user from logging in.
   - su - username - Lock the password of the specified user account, preventing the user from logging in.
   - sudo usermod -a -G GROUPNAME USERNAME -  Add an existing user to the specified group. The user is added to the group without removing them from their current groups.

## User System Information Commands

   - uname - Print System Information 
   - whoami - Display Current Username
   - df - Show disk space usage 
   - du Estimate file and directory sizes 
   - free - Display the memory usage information (free -h)
   - uptime - Show system uptime 
   - lscpu - Display the CPU information
   - lspci - List of PCI devices
   - lsusb - List of USB Devices

## Networking Commands

   - ifconfig - Display network interface information
   - ping - Send ICMP echo requests to a host
   - netstat - Display network connections and statistics
   - ss - Display network socket information
   - ssh - Securely Connect to a remote server
   - scp - Securely copy files between hosts 
   - wget - Download files from the web 
   - curl - Transfer data to or from a Server 

  - Today Sessions Notes:


  - Student work:
  - Write an Article & post it on LinkedIn Linux Commands
  - Reference Article:- https://lnkd.in/dBm2UkbC
 
[← Previous Day](../day03/README.md) | [Next Day →](../day05/README.md)
