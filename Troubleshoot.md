# Troubleshooting
**Issues with Ushahidi Services:**

- Go into Applications > System Tools > MATE Terminal 
- Change the directory from ‘cd’ to platform-client
- Use ‘ls -a’ command to peruse directory contents
- Use ‘cat .env’ command
    - Allows user to find .env file
- Run ‘ifconfig’ command to verify that either two addresses below match up
    - Enpos3 - inet address
    - *Enpos8 - inet address
