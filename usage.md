<img src="https://s3.amazonaws.com/masterminer/mn_logo.svg" alt="Masterminer" width="300px"/>

# HOW TO HOST YOUR OWN MASTERNODE 
1. Register and login at https://masterminer.tech/
<img src="https://s3.amazonaws.com/masterminer/docs/mu_login.png" alt="Masterminer" width="500px"/>

2. Click Dashboard and enter your Masternode's `Preferred Name, Masternode Private Key,   
Transaction ID, Index and Payment details` (*for MasterMiner’s subscription fee*)  
*Note:  masternode private key is not your wallet private key. This key only allows us to verify your  
masternode ownership while having zero control over your funds.*   
<img src="https://s3.amazonaws.com/masterminer/docs/mu_deploy.png" alt="Masterminer" width="500px"/>

3. After entering all required information in the create node process, click **DEPLOY**.   
Your Masternode will show up on your Dashboard once deployed. (*this process may take up to 5 mins*)

4. Select the recently deployed Masternode. On the edit dropdown, Select **Conbfig**, copy the *masternode configuration text* and paste it somewhere easily accessible. We will use this soon.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_dashboard.png" alt="Masterminer" width="500px"/>

5. Leave Masterminer site and open your wallet app (QT Wallet).   
Notice the *out of sync* status and the green loader bar at the bottom.   
The indicator will go away once your wallet is fully synchronized with the network. Please wait for it.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletboot.png" alt="Masterminer" width="500px"/>


6. Select the **Tools** menu and click **Open Masternode Configuration File**. A file will open in a text editor.  
Paste the masternode configuration from Masterminer config dashboard (step #4), then save and close the file.   
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletsettings.png" alt="Masterminer" width="500px"/>  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletconfig.png" alt="Masterminer" width="500px"/>  
Alternatively, if the Masternode config file is not showing up using the wallet menu,  
search for the `masternode.conf` in this location:   
**[MacOS]**  `:/Users/[your_username]/Library/Application Support/SyscoinCore`
**[Windows]** `:\Users\[your_username]\AppData\Roaming\SyscoinCore`
Open the file using a text editor and replace its content with the masternode configuration from   
Masterminer config dashboard (step #4), then save and close the file.

7. Close the wallet app and reopen it. When the synchronization is successful, the green status bar should no longer be visible.  
Click the Masternodes tab and select **Initialize All**.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_synced.png" alt="Masterminer" width="500px"/>  

8.  Wait up to 2 hours and check the *Status column* for ENABLED status. Once shown ENABLED, you can close the Wallet and enjoy your rewards!  
However, if the status is not shown as  ENABLED after 2 hours, repeat [step #7]. Wait for it to synchronize and repeat step #8 until ENABLED status is shown.  


### Masternode Deployment States
<img src="https://s3.amazonaws.com/masterminer/docs/MasterMiner_States.jpg" alt="Masterminer States" width="500px"/>  

#### If you encounter any issues.  Please [reach out to our community](https://t.me/joinchat/HL9uVRK4iDSI6y0Y_VCYjg) for support.


