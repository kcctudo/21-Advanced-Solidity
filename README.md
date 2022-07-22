# 21-Advanced-Solidity. 
# This file will demonstrate a deployment of a contract, minting of token and crowd sale of token.

The image below demonstrates the deployment of contract KaseiCoinCrowdsaleDeployer. After deployment a crowdsale address 0xb8f43EC36718ecCb339B75B727736ba14F174d77 and a token address 0x5C9eb5D6a6C2c1B3EFc52255C0b356f116f6f66D are created.

![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/deployed_contract.png)

The next 2 images demonstrate the loading of crowdsale.  A KaseiCoinCrowdsale was correctly picked as a contract.
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/load_crowdsale.png)
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/load_crowdsale2.png)

The next 2 images demonstrate the loading of token.  A KaseiCoin was correctly picked as a contract.
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/load_token.png)
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/load_token2.png). 

The next image demonstrates the functionality of purchasing a token.  The image shows 50 wei was successfully raised for the chosen wallet of address 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4.  It also shows the token address 0x5C9eb5D6a6C2c1B3EFc52255C0b356f116f6f66D. 
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/purchase_token.png). 
The next image demonstates that token was successfully purchased.  The balance of the account 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4 is reflected by 50 wei
![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/balance_token.png). 

The next image image demonstrate the functionality of token.renounceMinter() function.  The account 0x5B38Da6a701c568545dCfcB03FcB875f56beddC4 has renounced its mintability and hence the error message "he transaction has been reverted to the initial state.
Reason provided by the contract: "MinterRole: caller does not have the Minter role".
Debug the transaction to get more information." when the account owner tried to mint. 

![alt text](https://github.com/kcctudo/21-Advanced-Solidity/blob/main/renounce.png).
