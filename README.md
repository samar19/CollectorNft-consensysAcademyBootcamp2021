# CollectorNft-consensysAcademyBootcamp2021


CollectorNft Overview
*********************
 NFT based Photo MarketPlace is the peer-to-peer Marketplace for buy and sell of photos which was uploaded by users.
Even if user has smartphone which include function of camera, anyone can become sellers by uploading photos in this MarketPlace.
It mean that if user who is seller live in poor region and doesn't has bank account and so on, they can earn money by selling photos in this marketplace.
All of being uploaded photos are tokenized as NFT（Non-Fungible token).
Uploaded photos buy/sell 
 
 
 architecture of the app 
***********************
CollectorNft app will have three parts:
( back-end front-end and nft smart contract ) when the user first uses CollectorNft app the front-end is loaded in the web browser the front-end sends a request to the smart contract of the nft to know the url of the metadata the metadata of an nft is some extra info that is too big to be stored on blockchain so we only store a pointer of this info on the blockchain the front-end gets this metadata url and with it it sends a request to the backend the backend answers with the metadata of the token that's a json document in this json document
we also have the url of the image of the nft this image can be stored on any server but in this case that's going to be on the same server as the metadata so our front-end fetches the image from the server and display to the user as well as the metadata


Stack
*******
Solidity - Object-oriented, high-level language for implementing smart contracts.
Bootstrap 4 - CSS framework for faster and easier web development.
React.js - JavaScript library for building user interfaces.
web3.js - Allows users to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.
Truffle - Development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM).
Ganache - Personal blockchain for Ethereum development used to deploy contracts, develop DApps, and run tests.
