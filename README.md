# ETH-Vault
## Overview 🪙
A decentralized ETH bank with the tools necessary to maintain a secure environment.
## Features 📃
* Deposit -> Deposit the amount of ETH you want, without limits.
* Withdraw -> Withdraw ETH easily.
* Admin -> Have the power to perform functions only permitted for the user who deploys this smart contract.
* Limit -> To prevent theft or questionable behavior, a certain limit of ETH is allowed to be withdrawn per hour.
* Black list -> Add users to a blacklist and prevent them from depositing or withdrawing within this bank.
* Pause -> In case of emergency, you can pause all transactions within the bank to prevent unwanted losses to your users' assets.
* Adjustable -> Set the amount of ETH you want as the withdrawal limit per hour.
## Technical details ⚙️
* Integrated Development Environment -> Remix (Ethereum IDE).
* Solidity Compiler Version -> 0.8.24.
## Deploying the contract 🛠️
1. Open Remix IDE. Available at https://remix.ethereum.org.
2. Go to the "File explorer" tab and create a new file with the .sol extension in the "Contracts" folder.
3. Copy the ethvault.sol code and paste it into the .sol file you created.
4. Go to the "Solidity compiler" tab and select version 0.8.24.
5. Compile the code by pressing CTRL + S if you are on Windows, or COMMAND + S if you are on Mac OS.
6. If you find no errors, go to the "Deploy and Execute Transactions" tab and select your "Environment" and "Account".
7. Go to the deploy section and in the "MaxWithdrawPerHour" box enter the maximum amount of ETH (in WEI) you can withdraw per hour. In the "admin" box, enter the address of the user who will be in charge of managing the bank.
8. Finally, click on "Transact" so that the bank starts operating
## Contract interface details 💻
* addToBlackList ->  Add a user to the blacklist to prevent them from making deposits and withdrawals within the bank.
* depositETH -> Deposit ETH from your address to the bank.
* modifyMaxWithdrawPerHour ->  Sets the limit of ETH (in WEI) that can be withdrawn per hour.
* pauseTransactions -> Pause all bank transactions. 
* removeFromBlackList -> Remove a user from the blacklist.
* unpauseTransactions -> Resume all bank transactions.
* withdrawETH -> Withdraw ETH from the bank to your address.
* admin -> Check the address of the contract administrator.
* blocked -> Check if a user is blacklisted.
* maxWithdrawPerHour -> Check the maximum ETH (in wei) available to withdraw per hour.
* paused -> Check if the contract is paused.
* userBalance -> Check the amount of ETH (in WEI) you have saved in the bank. 

CODE IS LAW!
