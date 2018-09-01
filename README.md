<p align="center"><img src="logo.svg"></p>


# MamboCoin smart contract
* Standard : ERC20
* Name : Mambo Coin
* Decimals : 18
* Fiat dependency : No
* Tokens locked : Yes

* MamboCoin - Token contract
* Block Swap functionlity
* Configurator - contract with main configuration for production


## How to manage contract
To start working with contract you should follow next steps:

Compile it in Remix with enamble optimization flag and compiler 0.4.19
Deploy bytecode with MyEtherWallet.
Call 'deploy' function on addres from (3).


* Wallets with ERC20 support
* MyEtherWallet - https://www.myetherwallet.com/
* Parity
* Mist/Ethereum wallet

*Investor must not use other wallets, coinmarkets or stocks. Can lose money.*

Token counts.

* Main network configuration
* Minimal insvested limit : 0.04 ETH

## Smart contract important segment description.
MamboCoin token uses ERC20 standards and we have some other function to perfectly and smoothly run crowdsale, important functionality is described below.

### approve()
Aprove the passed address to spend the specified amount of tokens on behalf of sender.

### mint()
Mint _value amount tokens for _address.

### finishMinting()
Function to stop minting new tokens.

### setMintAgent()
Owner can allow a crowdsale contract to mint new tokens.

### transfer()
Transfer token to other account.

### transferFrom()
Transfer tokens from other account based on decreaseApproval

### transferOwnership()
Allows the current owner to transfer control of the contract to a newOwner.

### allowance
Check the approved tokens from the account

### balanceOf()
Check the balance of an account.

### mintAgents()
List of contracts that can mint coins.

### finishMinting()
Function to stop minting new tokens and disable all mint agents.

### totalSupply()
Check the total supply of the tokens