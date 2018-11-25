# Troubleshooting
**Issues with Ushahidi Services:**
- Go into Applications > System Tools > MATE Terminal 
- Change the directory from ‘cd’ to platform-client
- Use ‘ls -a’ command to peruse directory contents
- Use ‘cat .env’ command
    - Allows user to find .env file
- Run ‘ifconfig’ command to verify that either two addresses below match up
    - Enpos3 - inet address
    - Enpos8 - inet address
- Run ‘pluma .env’ command
    - This will open up a simple text editor to change the address if there is a discrepancy 
- Edit backend URL (1st one) 
    - What URL should be: 192.168.56.101
- Save the edit
- Run cat .env in terminal again to ensure it was correct/saved
- In MATE Terminal:  run Gulp/npm commands to organize Javascript
- Run ‘npm run watch’ command
    - NOTE: Should be consistent with current step 12 now
    - Two URLS should be present
    - To use local URL - click it

**How to Fix Implementation Problems**
#### Step 16 Error Correction:
- Go into Applications > System Tools > MATE Terminal
- Change directory 'cd' to platform client (if not already done).
- Look at contents of directory using command 'Is-a' (different than command 'Is' - shows hidden files/folders).

