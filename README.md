# *Token Crowdsale*
---

**Welcome to my repository for the Martian Token Crowdsale. Please explore the codebase!** <br />

>“Don’t stay in bed, unless you can make money in bed.” – George Burns
---
## Analytical Summary

This project creates a fungible token that is ERC-20 compliant and that is minted by using a crowdsale contract from the OpenZeppelin Solidity Library. The crowdsale contract manages the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. The contract mints the tokens automatically and distributes them to buyers in one transaction.

---

## Technologies

This project leverages Solidity compiler 0.5.0 that is run in the Remix IDE https://remix.ethereum.org

---

## Usage

To use this project run the code in Remix, using the compiler 0.5.0. Deploy the crowdsale to a local blockchain using Remix, MetaMask and Ganache.

---
## Methodology

Upload the KaseiCoin.sol file into the Remix. 
Compile the smart contract:

![snippet of our code](Images/image0.1.png)

Upload the KaseiCoinCrowdsale.sol file into the Remix.
(Compiling the first part of the contract - not necessary)
![snippet of our code](Images/image0.2.png)

Compile the smart contract:
![snippet of our code](Images/image0.3.png)

Select Injected Provider as your Environment and deploy the KaseiCoinCrowdsaleDeployer contract. Select one of your MetaMask accounts (here account 4) as your wallet.

![snippet of our code](Images/image1.png)

You will loose some of your Ethereum currency on gas fees, you can see it on your MetaMask account:

![snippet of our code](Images/image2.png)

And also on your Ganache blockchain:

![snippet of our code](Images/image3.png)
Select your KaseiCoinCrowdsale contract then enter your crowdsale address from your KaseiCoinCrowdsaleDeployer contract and insert it in the field next to 'At Address', then click 'At Address'.

Select your KaseiCoin contract then enter your token address from your KaseiCoinCrowdsaleDeployer contract and insert it in the field next to 'At Address', then click 'At Address'.

![snippet of our code](Images/image4.png)

To purchase tokens add value in Weis at the top of the Remix site (I put 10 Wei):
![snippet of our code](Images/image5.png)

Then in the KaseiCoinCrowdsale contract add beneficiary - one of your MetaMask acdress and click BuyTokens:

![snippet of our code](Images/image6.png)

You can see on your MetaMask account that you get charged some gas fee for this transaction.
![snippet of our code](Images/image7.png)

You can see the value of your new tokens on Ganache:

![snippet of our code](Images/image8.png)

To purchase tokens for your second account add value in Weis at the top of the Remix site (I put 13 Wei):

![snippet of our code](Images/image9.png)

You can see on your MetaMask account that you get charged some gas fee for this transaction.
![snippet of our code](Images/image11.png)

You can see the value of your new tokens on Ganache:
![snippet of our code](Images/image12.png)

You can also confirm the value of the Tokens by clicking on the balanceOf button in your contract:
![snippet of our code](Images/image13.png)

You can approve both of these MetaMask accounts in the contract (it again cost you some ETH in gas fees):
![snippet of our code](Images/image14.png)

![snippet of our code](Images/image16.png)

And increase allowance for both of them (you will loose money in ETH in gas fees):
![snippet of our code](Images/image17.png)

![snippet of our code](Images/image18.png)

![snippet of our code](Images/image19.png)

You can also transfer money in the newly issued Tokens from one account to another:

![snippet of our code](Images/image20.png)

![snippet of our code](Images/image21.png)

and see the altered balance after such transaction in both accounts:
![snippet of our code](Images/image22.png)

![snippet of our code](Images/image23.png)

You can keep track of your actions for your accounts in ETH in Ganache.
![snippet of our code](Images/image24.png)
---

## Contributors

Brought to you by Katerina Gawthorpe.

---

## License

MIT