# Allocated-Presale / Crowdsale

Post deployment crowdsale

How to sell tokens from an aldready existing contract at a new crowdsale contract.

<h3>The contracts used are taken from OpenZeppelin</h3>

<h4>Crowdsale contract: @openzeppelin-contracts/v2.5.0/contracts/crowdsale/Crowdsale.sol</h4>

The contract was compiled in Remix and flattened with Remix built-in flattener. 

*Note: the remix flattener doesn't always put the different parts of the contract in the right order when flattening
so you might have to manually move them around until they are positioned correctly*

Deploy your crowdsale contract at the contract address of the token you wish to sell.

However, if you copy the ABI then you can interact with the contract at https://app.mycrypto.com/interact-with-contracts

Just put the address in and paste the ABI, and save the contract in case you need to interact with it at a later date.

rate = 5,000 (5000 token for 1 BNB)

wallet = Wallet for receiving BNB

token = CA of token to be sold

Now you should have the tokens either in your wallet or at the contract address which you have access to. All that is left is to 
transfer the amount of tokens you wish to sell to the newly deployed crowdsale contract.


Crowdsale contract at testnet:  https://testnet.bscscan.com/address/0xdf2c17b1c95251d5f4025bfced1473c69624baea

