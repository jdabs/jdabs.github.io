---
layout: post
title:  "Get BRC-20 Tokens with Unisat"
author: "jdabs"
---

## What is BRC-20 Tokens?

BRC-20 tokens are an experimental technology on the Bitcoin blockchain. It inscribes JSON data to the blockchain, which manages the state of the tokens. The JSON data
controls the contract behind the token, minting, and transferring. The main protocol running the experiment is 
[Ordinal Inscriptions](https://research.aimultiple.com/ordinal-inscriptions/tions), which is the concept of applying metadata to the Bitcoin blockchain; in the case
of BRC-20 tokens, this is JSON metadata.

## Unisat Wallet
Unisat wallet is a browser extension that takes care of the management of your BRC-20 tokens, such as your balance, minting, and transferring tokens in 
your balance. It does this without running a full node (downloading the entire Bitcoin blockchain), which early implementations of Ordinals required. 

The wallet also has a companion website, https://unisat.io, which syncs with the wallet. The website acts as a GUI interface where you can create new tokens, 
mint existing tokens, or engage in a marketplace where you can buy and sell tokens.

![Unisat Token Screen](/assets/token-screen.png)

## Download and create your Unisat wallet

First off you need to install the Unisat extension and set up a wallet.

### 1) Use the Chrome extension download link on https://unisat.io
Install the Extension from the Chrome extension store. The button on unisat's website takes you directly there.

![Unisat website extension download button](/assets/unisat-website-download-ext.png)

Note: You must be on the Chrome browser

### 2) Set up the wallet
Open the extension and select to create a new wallet. Write down the words that make up the seed phrase. You will also be asked to create a password, which you
will always need to use when opening the wallet later.

![Unisat Create Wallet](/assets/unisat-create-wallet.png)

## Fund the wallet and mint a token
You need sats (the smallest units of Bitcoin) in order to mint and create tokens. These sats are used to pay the mining fee to inscribe data to the 
blockchain, and they are used as the sats that the token data is inscribed to. These are the sats you can transfer and sell since they are the record of your 
BRC-20 tokens. Unisat handles which sats are the ones that contain the data so that you don't accidentally spend them on mining fees.

### 1) Receive funds
Open the Unisat extension and click receive. Send a small amount of sats to the address shown, either with the QR code or the address shown below the QR code. You do not need to send much to get your first BRC-20 tokens. You need just enough to pay the mining fees, so USD$20 worth of sats isn't a bad start.

Some exchanges or wallets may not recognize the address Unisat generates. As a workaround, send the sats to an Exodus wallet first, and from there, send to the Unisat receive address.

![Unisat Receive](/assets/unisat-wallet-recieve.png)

### 2) Find an existing token to mint

Go to https://unisat.io and click the BRC-20 menu item. Switch the filter to "In-Progress". This means you'll only be shown tokens that can still be
minted and are not 100% minted. 

One hundred percent minted means the whole supply has already been minted and the only way to get that token would 
be if someone transferred it to you, either through a marketplace or over-the-counter transaction.

![BRC-20 Search](/assets/brc20-search.png)

### 3) Mint the token
There's no perfect science as to what's a good token. It's not as though one has better "technology" over another. They all do the same thing under the hood: inscribe JSON data to the blockchain. The main difference between them is the ticker symbol. There's a general belief that you should get one with a sensible supply and limit per mint. For example, a coin with a billion supply and only 1,000 limit per mint would take a long time to mint 100% and generate some scarcity.

Note: limit per mint is the maximum amount of coins you can get each time you do a transaction. So if you want 10,000 tokens with a limit per mint of 1,000, you have to create 10 transactions and pay 10 mining fees.

Click the "Mint Directly" button to go through the creating and broadcasting the mint transaction. Afterwards, the token will show up in your balance in your Unisat
wallet.

![Unisat mint token](/assets/unisat-mint-token.png)

Balance:

![Unisat balance](/assets/unisat-balance.png)



