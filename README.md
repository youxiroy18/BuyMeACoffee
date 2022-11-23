# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```


**Developing a  Smart Contract  with Solidity and deploying it on the blockchain**  might sound daunting at first: solidity, security,  gas  optimization, developer environment, and  gas  fees, are only some of the things you’ll need to go through to host your code on the  blockchain.

Luckily though, in the last few months, a lot of tools have been released for developers to make their Smart contracts development jobs much easier.

Tools like the  **OpenZeppelin**  **Wizard**  that offers developers click and write functionalities to create composable and  **secure smart contracts**  in no time, used with Web3 developer tools like  **Alchemy**, make the experience of writing and deploying code on the  blockchain  easy, fast, and reliable like never before.

In this tutorial, you're going to learn  **how to develop and deploy an ERC721 (NFT)**  smart contract using  **Alchemy, OpenZeppelin, Remix, and Ethereum Goerli.**

More precisely, you will learn:

-   How to write and modify the smart contract using OpenZeppelin and Remix
-   Get free Goerli ETH using  **[https://goerlifaucet.com/](https://goerlifaucet.com/)**
-   Deploy it on the Ethereum Goerli testnet blockchain to save on gas fees
-   Host the NFT tokens metadata on IPFS using Filebase.
-   Mint an NFT and visualize it on OpenSea.

You can also follow the video tutorial:
https://cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FveBu03A6ptw%3Ffeature%3Doembed&display_name=YouTube&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DveBu03A6ptw&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FveBu03A6ptw%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube

Let’s start by creating the  smart contract.

## 

Develop the ERC721 Smart Contract With the OpenZeppelin Contract Wizard.

[](https://docs.alchemy.com/docs/how-to-develop-an-nft-smart-contract-erc721-with-alchemy#develop-the-erc721-smart-contract-with-the-openzeppelin-contract-wizard)

As said before, in this tutorial, you're going to  **use the OpenZeppelin Wizard to create the smart contract**, for two main reasons:

-   It’s secure.
-   It offers standard smart contracts.

When it comes to writing smart contracts,  **security**  is key. There are tons of examples of smart contract exploits that have seen hundreds of millions of dollars stolen by malicious actors due to bad security.

_You don’t want someone to steal all of your precious cryptos or NFTs once you’ll deploy on the blockchain right?_

**OpenZeppelin serves this purpose,**  being one of the biggest maintainers of smart contract standards (ERC20, ERC721, etc), allowing developers to use thoroughly audited code to develop reliable contracts.

The first thing you'll need to do to develop our ERC721 NFT smart contract is to  [**go on the Open Zeppelin Smart contract wizard page.**](https://docs.openzeppelin.com/contracts/4.x/wizard)

Once on the page, you will see the following editor:
