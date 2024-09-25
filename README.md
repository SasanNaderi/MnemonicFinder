# scraped over 1 BTC within a few weeks (and keep doing it)

> **UPD: It’s been a while. I’m giving out only a few more copies and close down the offer in order not to make it too hype.**

People often forget about security and publicly post data that should not be shared. This also applies to credentials for recovery of cryptocurrency wallets: private keys and mnemonic seeds.

About two years ago, I came up with an idea to create a program that could automatically scrape such data on the Internet, automatically check the balance of wallets and insert everything in a readable table. A month later I did it…

Below I will attach all the proofs, tell you how the program works, and why I decided to share it.

**Disclaimer №1**

> *There are many programs on the Internet that allegedly do something similar by creating, or guessing, private keys. This is bullshit: to randomly guess a private key with balance, even with a very powerful computer, you will need about 250 years. We are only looking for those private keys that people have foolishly posted themselves.* ***This is not another shitty mnemonic generator, it’s a professional scraper.\***

**Disclaimer №2**

> *We leave all ethical issues aside.*

# Proofs

Good for me that I screenshot everything, and I can show what the program looked like when I discovered some wallets with balance.

**Case 1**

One of the big wins. This is also a good example of how multifunctional the program is. At the beginning of November, I decided to implement scraping not only from text, but also from images. The program finds keywords in the text of images and analyzes them according to a template. And…

![img](https://miro.medium.com/v2/resize:fit:700/0*i5T0Oj_E5s0SC0Zx.png)

That’s what it looked like in the program. Note BIP49 BTC balance.

I followed the link with the leaked seed phrase https://www.ellipal.com/blogs/support/set-up-cold-wallet and saw that someone used a sample as a wallet for storing 0.48 BTC (!!!)

Here are the wallet transactions on blockchain: https://www.blockchain.com/btc/address/3GDqeB46Ng9u2WubVB3DEFXNWpZAm1a5HK

![img](https://miro.medium.com/v2/resize:fit:700/0*bDgPuI52hHLfd4MQ.png)

I recovered the wallet in Ellipal app and transferred bitcoins to myself.

![img](https://miro.medium.com/v2/resize:fit:700/0*NSa-fYQP-jaX5wzK.png)

I also found there 178 Polkadot coins which was nice…

> *You can (and should) recover the wallet using the discovered mnemonic seeds in Ellipal app and check everything yourself.*

![img](https://miro.medium.com/v2/resize:fit:700/0*1EnyFKYPubR6gkbw.png)

This is my wallet in Trust Wallet app, where I transferred the funds.

**Case 2**

Someone leaked their mnemonic seeds to a wallet with balance on the forum.

![img](https://miro.medium.com/v2/resize:fit:700/0*iAKmGAHiOr2zlyI1.png)

This is what it looked like in the program. A little of bitcoins…

I followed the link https://bitcoin.stackexchange.com/questions/110571/account-extended-public-key-from-mnemonic and saw that someone leaked their mainnet mnemonic seeds. Ok…

![img](https://miro.medium.com/v2/resize:fit:700/0*rniEeNr_ljmRlLbx.png)

So I recovered the wallet in Electrum and transferred the funds to myself. Here are the wallet transactions on blockchain: https://www.blockchain.com/btc/address/bc1qxj3macvwh6z6tfgc2npeh0t46l3g49d80dh0es

![img](https://miro.medium.com/v2/resize:fit:700/0*AO6jji9tqBiWLx_Q.png)

Incoming transaction on Thursday.

![img](https://miro.medium.com/v2/resize:fit:700/0*8di2h4CbjVb6avp1.png)

This is my wallet in Cake Wallet app, where I transferred the funds.

> *Again, recover the discovered wallet yourself and check out the transactions yourself.*

**Case 3**

One of recent examples. Someone published metamask password on the website: https://www.roch.by/page29862824.html

![img](https://miro.medium.com/v2/resize:fit:700/0*5t_xWgoaUt9e9Cmg.png)

So, I transferred 0.216 ETH (Arbiscan network) to my wallet: https://arbiscan.io/tx/0xa810b7035da8b0a87093e64502d180f6ab3668cd5c3934382febb79435454645

You can open the leaked wallet with the seed phrase and check the transaction yourself.

# How the program works

I don’t want to go into technical details too much: someone skilled enough for this will simply copy the program. In short, the bottom line is that the program googles and scrapes certain websites for everything that resembles mnemonic seeds and private keys:

\- phrases in English from the bip39 dictionary with a length of 12 and 24 words,

\- combinations of characters that start with 0x 64 characters long,

\- WIF private keys,

\- etc.

After that, the program processes the data:

\1. “Converts” mnemonic seeds and private keys into wallet addresses.

\2. Checks the balance of wallets.

\3. Summarizes the data in a table.

All I have to do is to check out the table from time to time, open wallets with a balance (in Trust Wallet, Metamask, Cake Wallet, Electrum or Ellipal) and transfer coins to myself.

You could try search seed phrases and private keys manually, but you won’t succeed: there are thousands published mnemonic seeds without balance and to find those with balances you would need a team of at least 1,000 people to check all the required websites 24/7.

# Pricing

The program with detailed instructions costs 0.04 BTC. Based on my experience, it will pay off within the first week. I will sell a very limited number of program copies for a limited period of time.

# What you get:

\1. The program

\2. Installation instructions

\3. Instructions for use

\4. Instructions for hiding traces in the blockchain. Roughly speaking: if you simply transfer bitcoins or ether from someone else’s wallet to your own, and then withdraw these to fiat, you can easily be tracked and caught.

\5. Instructions for safe withdrawal of cryptocurrencies to bank accounts: so that the banks and the tax services are not too curious.

# How to get

I am very worried about security, so the purchase procedure is aimed at my maximum privacy and is not discussed.

1. Email me at yeameta@gmail.com stating you’re going to buy the program.
2. Pay 0.04 BTC to my Bitcoin wallet bc1phq9nfy7pxdpz95ua6288gfy5gafcu30g40mgtkk2l928xzgudmrqwwp4r2
3. After payment I send the program and instructions to your email. If you are going to have any questions during the setup of the program, I will help.

**Please note: I only accept payment for the program to wallet addresses indicated in the case examples set out above. If someone offers you to pay to another wallet, this person does not own my program.**