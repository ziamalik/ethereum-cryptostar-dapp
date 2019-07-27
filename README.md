# Ethereum Cryptostar DAPP
Cryptostar DAPP - Based on Ethereum ERC-721 Token Standard

* ERC-721 Token Name: `Fancy Crypto Stars`
* ERC-721 Token Symbol: `FCS`
* Contract Address on Rinkeby: `0x7a178bd4c11435a98400EAf65836e1E4D921fa53`
* Etherscan Link: <https://rinkeby.etherscan.io/address/0x7a178bd4c11435a98400eaf65836e1e4d921fa53>

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


