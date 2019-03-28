# Troubleshooting
**If you finish the step trying to access the Ushahidi VM using the web browser via localhost or IP address and you get a "server not found" error:**
1. Go into Applications > System Tools > MATE Terminal 
1. Change the directory from ‘cd’ to platform-client
1. Use ‘ls -a’ command to peruse directory contents
1. Use ‘cat .env’ command
    1. Allows user to find .env file
1. Run ‘ifconfig’ command to verify that either two addresses below match up
    1. Enpos3 - inet address
    1. Enpos8 - inet address
1. Run ‘pluma .env’ command
    1. This will open up a simple text editor to change the address if there is a discrepancy 
1. Edit backend URL (1st one) 
    1. What URL should be: 192.168.56.101
1. Save the edit
1. Run cat .env in terminal again to ensure it was correct/saved
1. In MATE Terminal:  run Gulp/npm commands to organize Javascript
1. Run ‘npm run watch’ command
    1. NOTE: Should be consistent with current step 12 now
    1. Two URLS should be present
    1. To use local URL - click it
