# crypto-gamble
A discord bot that you can gamble real money (crypto) against the house or other players.

---

## Table of Contents
You're sections headers will be used to reference location of destination.

- [Description](#description)
- [How To Setup](#how-to-setup)
- [Dependencies](#dependencies)
- [References](#references)
- [Author Info](#author-info)

---

## Description

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

Copy the token and place it when it says 'putTokenHere'.
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
 
```
    
---

## Dependencies

There are 11 dependencies you need to install to have the program to work.

- @discordjs/builders
- discord-api-types
- @discordjs/rest
- shuffle-seed
- body-parser
- discord.js
- mongoose
- nodemon
- express
- dotenv
- axios

Just use npm i {package-name} in your terminal to install them.

---

## API Reference

```html
    <p>dummy code</p>
```

---

## References
- Crypto Deposits - [Apirone](https://apirone.com/)
- Crypto Prices - [CryptoCompare](https://cryptocompare.com)
- Provably Fair - [Random.org](https://random.org/)

---

## Author Info

- Discord - [vol#0001]()
- Website - [Solo.to](https://solo.to/x2vol)
