<img src="https://s3.amazonaws.com/masterminer/mn_logo.svg" alt="Masterminer" width="300px"/>


#### When will masternode pooling service be available?
Masternode pooling for **Syscoin** is currently supported. More coins to come upon request.


#### How do I keep my masternode updated?
We've got you covered! We'll be monitoring and maintaining the masternodes by keeping them up to date.

#### How can I pay for the service?
Masterminer.tech currently accepts the following payment options:   
`Credit cards, BTC, ETH, BCH, LTC, SYS`

*** 

## HOW TO HOST YOUR OWN MASTERNODE 

#### What is the status of my Masternode? | What does “Error code: -32603” mean?

<img src="https://s3.amazonaws.com/masterminer/docs/MasterMiner_States.jpg" alt="MasterminerStates" width="500px"/>

#### I don’t see a Masternode tab in my wallet app…

1. Select **Settings** on the menu panel and click **Options**.

2. On the options window, select the Wallet tab and enable **Show Masternodes Tab** then click Ok.

3. Close and restart the wallet app to see the Masternodes tab.

<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_01.png" alt="MasterminerStates" width="500px"/>

#### Where do I find my Masternode Private Key?

1. Select **Tools** on the menu panel and click **Debug Console**.

2. Type `masternode genkey` on the command input and press Enter. 

3. View console output to get the masternode key.

<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_02.png" alt="MasterminerStates" width="500px"/>


#### Where do I find my txid and index?

1. Select **Tools** on the menu panel and click **Debug Console**.

2. Type `masternode outputs` on the command input and press Enter. 

3. View console output to get the txid (the first item in the pair underlined in **red**)   
and index (the second item in the pair underlined in **blue**) . Exclude the quotation marks (“).

<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_03.png" alt="MasterminerStates" width="500px"/>

#### I sent the 100k SYS collateral but I don't see it in my Masternode outputs…

1. Select **Tools** on the menu panel and click **Debug Console**.

2. On the options window, select the **Wallet tab** and
 enable **Enable coin control features** then click Ok.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_04a.png" alt="MasterminerStates" width="500px"/>

3. Back on the main window, select  **Send** on the toolbar and click  *Inputs*.  
<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_04b.png" alt="MasterminerStates" width="500px"/>  

4. On the Coin Selection window, click all checkboxes with an amount less than 100,000, then press Ok.
<img src="https://s3.amazonaws.com/masterminer/docs/mu_faq_04c.png" alt="MasterminerStates" width="500px"/>

```This step is essential to specifically tell the wallet where to get the funds during transfer Without this, your wallet may take away some funds from your reserved 100K, thus making it ineligible for Masternodes.```

5. Send 100,000 SYS to your wallet.


#### If you encounter any issues.  Please [reach out to our community](https://t.me/joinchat/HL9uVRK4iDSI6y0Y_VCYjg) for support.






