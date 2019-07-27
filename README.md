# ethereum-cryptostar-dapp
Cryptostar DAPP - Based on Ethereum ERC-721 Token Standard

* ERC-721 Token Name: `Fancy Crypto Stars`
* ERC-721 Token Symbol: `FCS`
* Truffle Version: `5.0.29`
* OpenZeppelin Version: `2.3.0`

Run `npm install` to install all the dependencies.

To deploy as your own token on Rinkeby Network, 
* First create 2 files:
1. `.secret-mnemonic` - Your secret metamask account mnemonic
2. `.infura-project-id` - Your Infura project id

* Run the following:
```
truffle migrate --reset --network rinkeby
```


