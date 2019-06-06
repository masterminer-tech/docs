<img src="https://s3.amazonaws.com/masterminer/mn_logo.svg" alt="Masterminer" width="300px"/>

# HOW TO HOST YOUR OWN MASTERNODE 
1. Register and login at https://masterminer.tech/
<img src="https://s3.amazonaws.com/masterminer/docs/mu_login.png" alt="Masterminer" width="500px"/>

2. Click Add Bide and enter your Masternode's `Preferred Name, Masternode Private Key,   
Transaction ID, Index and make sure your account is funded. 

<img src="https://firebasestorage.googleapis.com/v0/b/mm-dev-v2.appspot.com/o/Screen%20Shot%202019-06-05%20at%2010.06.14%20PM.png?alt=media&token=c5483b06-364f-4c2a-870a-a1e3d3a9f607" alt="Masterminer" width="500px"/>

3. After entering all required information, click **Submit**.   
You will get a confirmation and your masternode will show up on your Dashboard after few minutes. 

4. Once the node shows up on your dashboard, select the "more" icon and select **Configuration**. Then proceed to copy the *masternode configuration text* and save it somewhere easily accessible. We will use this soon.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_dashboard.png" alt="Masterminer" width="500px"/>

5. Leave Masterminer site and open your wallet app (QT Wallet).   
Notice the *out of sync* status and the green loader bar at the bottom.   
The indicator will go away once your wallet is fully synchronized with the network. Please wait for it.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletboot.png" alt="Masterminer" width="500px"/>


6. In the menu click **Tools** and select **Open Masternode Configuration File**. A file will open in a text editor.  
Paste the masternode configuration from Masterminer dashboard (step #4), then save and close the file.   
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletsettings.png" alt="Masterminer" width="500px"/>  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_walletconfig.png" alt="Masterminer" width="500px"/>  
Alternatively, if the Masternode config file does not open from the wallet menu,  
search for the `masternode.conf` file in these locations:   

**[MacOS]**  `/Users/replace_with_your_username/Library/Application Support/Syscoin`

**[Windows]** `\Users\replace_with_your_username\AppData\Roaming\Syscoin`


7. Restart your qt wallet. wait for it to sync. the green status bar should no longer be visible.  
Click the Masternodes tab and select **Initialize All**.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_synced.png" alt="Masterminer" width="500px"/>  

8. The *Status column* in qt wallet should turned ENABLED after 30 minutes. Once shown ENABLED, you can close the Wallet and enjoy your rewards!  
However, if the status is not shown as  ENABLED after 2 hours, verify that [step #6] is correct and repeat [step #7]. Wait for wallet to synchronize and repeat step #8 until ENABLED status is shown.  


### Masternode Deployment States
<img src="https://s3.amazonaws.com/masterminer/docs/MasterMiner_States.jpg" alt="Masterminer States" width="500px"/>  

#### If you encounter any issues.  Please [contact us in-app](https://masterminer.tech) for support.


