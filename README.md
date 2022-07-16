## Table of Contents

- [Description](#description)
- [How To Setup](#how-to-setup)
- [Dependencies](#dependencies)
- [References](#references)
- [Author Info](#author-info)

---

## Description

This bot uses discord.js so you must have node.js installed to run this application. This bot has automatic litecoin deposits to play with real money, the commands will be listed below.

Games
- Blackjack
- Coinflip
- More coming soon

Crypto
- Prices - Lists BTC, ETH, LTC, & DOGE current price and percent increase/decrease.
- Deposit - Directly messages the user with a deposit address and QR code.
- Withdraw - Take in an address and amount and withdraws litecoin to the address.

Information
- Bal - Shows the user their cash balance.
- Profile - Gives information such as games played, wins, loses, wagered, profit, tipped, airdropped, etc.
- Leaderboard - Shows top 5 users in each category: Balance, Wagered, and Profit.

Fun
- Tip - Tips a user balance.
- Airdrop - Airdrops balance to anyone that clicks the join button.
- Giveaway - Gives away balance to one lucky winner.

Misc
- Provably Fair - Gives the verifiable provably fair information on the inputed game id.
- Help - Gives all the current commands with descriptions.

---

## How To Setup

In your env file there are 8 number of things you need to fill in!

```
BOT_TOKEN=
BOT_ID= 
GUILD_ID=
RND_API_KEY= 
MONGODB_SRV= 
APIRONE_WALLET_ID= 
APIRONE_TRANSFER_KEY= 
LOCALTUNNEL_URL=
```

First head to the [Developer Portal](https://discord.com/developers) and create an application, then create a bot in that application. 

To invite the bot to your server, you must head to OAuth2 -> URL Generator. 
![OAuth2](https://cdn.discordapp.com/attachments/997919313723924650/997919361920671744/IMG_0884.png)

Then you must select these boxs or the bot will not have the correct permissions, then copy the invite link at the bottom.
![Scopes](https://cdn.discordapp.com/attachments/997919313723924650/997919612647784570/IMG_0885.png)

Copy the bot token and place it when it says 'putTokenHere'.
```
BOT_TOKEN=putTokenHere
```

Next take the bots id and place it where it says 'putIdHere'.
```
BOT_ID=putIdHere
```

Next find the guild that you want to use your commands in, then copy the guilds id and put it where it says 'putIdHere'.
```
GUILD_ID=putIdHere
```

Next go to [API Dashboard](https://api.random.org/) at random.org and create an account, then create a free api key and put it where it says 'putApiKeyHere'.
```
RND_API_KEY=putApiKeyHere
```

Next go to [MongoDB](https://mongodb.com) create an account and sign in. Then create a cluster (A database) and select the free shared cluster. Make a username in password in the access area and whitelist your ip address. Then go to your database and click on connect -> connect to application -> and copy the string and put it where it says 'putSRVhere'. Make sure you replace <password> with the password you set earlier.
```
MONGODB_SRV=putSRVhere
```

Next go to [Apirone](https://apirone.com/) to create your hot wallet. Click Dashboard -> Create now -> Select wallet -> Next -> Select Litecoin -> Create. Now copy the Wallet id and place it where it says 'walletIdHere', and copy the transfer key and put it where it says 'transferKeyHere'.
```
APIRONE_WALLET_ID=walletIdHere
APIRONE_TRANSFER_KEY=transferKeyHere
```

Lastley type a bunch of random letters where it says 'prefixHere', this will make a custom url that looks like {prefix}.loca.lt, this is mandatory as you need this url running to recieve deposit callbacks. 
```
LOCALTUNNEL_PREFIX=prefixHere
``` 
 
To start the bot just run 'nodemon src/index.js' and everything should be good to go! If there are any errors [contact me](#author-info) and I will do my best to help you through your error!
 
Note: Editing any of the .env vairable names will mess up the bot, DO NOT change these at anytime.
---

## Dependencies

There are 11 dependencies you need to install to have the program to work.

- @discordjs/builders
- discord-api-types
- @discordjs/rest
- shuffle-seed
- body-parser
- localtunnel
- discord.js
- mongoose
- nodemon
- express
- dotenv
- axios

Just use npm i {package-name} in your terminal to install them.

---

## References
- Framework - [Discord.js](https://discord.js.org/)
- Crypto Deposits - [Apirone](https://apirone.com/)
- Crypto Prices - [CryptoCompare](https://cryptocompare.com)
- Provably Fair - [Random.org](https://random.org/)

---

## Author Info

- Discord - [vol#0001]
- Discord - [Server](https://discord.gg/)
