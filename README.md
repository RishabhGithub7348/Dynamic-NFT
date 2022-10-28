# Dynamic-NFT

Deployed Contract Address:
https://goerli.etherscan.io/address/0x554c45d9a1d6a3472b92037688f6952021384869
 
 Dynamic NFT on opeansea testnets:
 https://testnets.opensea.io/assets/goerli/0x554c45d9a1d6a3472b92037688f6952021384869/0
 
Dynamic-NFT Description


This project mints Dynamic NFTs that change based on the market price of an asset pair (for example, the BTC/USD asset price). When prices go up, its a bull trend and when the go down its a bear trend. We run Chainlink Keepers to have our smart contract automatically called at specified intervals so that on-chain logic checks the Chainlink Price Feed to see if there has been a change in price. Accordingly the minted NFTs dynamically alternate between the images below.

<div style="display:flex column-gap:"2rem"">
 <img src = "https://user-images.githubusercontent.com/75687649/198516307-5a09b3f4-09cd-4dab-a75d-a9d775d93dc0.png" style="width:300px">
 <img src = "https://user-images.githubusercontent.com/75687649/198516370-1f87c4ee-b75f-4be9-b489-a51ec1d509f7.png" style="width:300px">
 <img src = "https://user-images.githubusercontent.com/75687649/198516417-99be191a-0aa6-4bcf-a130-d7b72852700b.png" style="width:300px">
 <img src = "https://user-images.githubusercontent.com/75687649/198516460-b2b15483-3b95-407a-aa85-a970a0568234.png" style="width:300px">
 <img src = "https://user-images.githubusercontent.com/75687649/198516495-12441e4a-f6ab-47c5-b7a6-2371d1e48349.png" style="width:300px">
 <img src = "https://user-images.githubusercontent.com/75687649/198516525-86e51466-77a5-4e9c-85c4-bb1566fd4ed5.png" style="width:300px">
</div>


 
 


     

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


