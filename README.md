# Dynamic-NFT

Deployed Contract Address:
https://goerli.etherscan.io/address/0x554c45d9a1d6a3472b92037688f6952021384869
 
 Dynamic NFT on opeansea testnets:
 https://testnets.opensea.io/assets/goerli/0x554c45d9a1d6a3472b92037688f6952021384869/0
 
Dynamic-NFT Description


This project mints Dynamic NFTs that change based on the market price of an asset pair (for example, the BTC/USD asset price). When prices go up, its a bull trend and when the go down its a bear trend. We run Chainlink Keepers to have our smart contract automatically called at specified intervals so that on-chain logic checks the Chainlink Price Feed to see if there has been a change in price. Accordingly the minted NFTs dynamically alternate between the images below.

https://github.com/zeuslawyer/chainlink-dynamic-nft-alchemy/raw/main/ipfs/gamer_bull.png

     

The entire project is designed for ease of use by those new to Web3 and can be run from a Remix in-browser IDE and network environment.

using Hardhat,
using Truffle,
testing with Hardhat,
testing with Truffle, and
testing with Hardhat
You can even dig into Chainlink Smart Contract Examples to find more clever ways of extending your code!

TOOLING REQUIREMENTS
All you need to run this code is the Remix IDE running in your browser and a Metamask wallet. While this repo includes mocks for you to "mimic" Chainlink oracle services, for your Assignment you will need to deploy to the Rinkeby test network.

When on test networks you will need test Ether and test LINK tokens in your Metamask wallet.

⚠️ Be sure to use only test ethereum accounts in Metamask when developing. You don't want to lose or spend real money!

Branches
This repo is organized in "main". 

  It have Dynamic NFT (ERC721) smart contract code.
price-feeds has the code that adds Chainlink Data Feeds logic and functionality along with the implementation of the Keepers interface so that our NFT Contract is Keepers compatible.


