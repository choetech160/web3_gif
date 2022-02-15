# Web3 gif exchange / messenger

## Install

- clone this repository
- `npm install`
- `npm run start`

You should have a local server running on `localhost:3000` and see the following:

// image

## Environment

### API Key

For this to work properly, you need an api key from giphy. Otherwise the Gif will always be the default one. 

Add it to a `.env` file in `/src` 

```javascript
VITE_GIPHY_API = 'You api key'
```

### Metamask

The website will ask you to install metamask if this is not done. 
You will have to create 2 accounts, so you can send message to yourself, from one account to the other.

**Use the `Ropsten Test Network` , not the Mainnet!**

Now you can use a [faucet](https://faucet.egorfine.com/) to receive ETH on one of your account and test the website.


## Usage

On the Eth card, you should see your current account address

// show eth card

In the form bellow, `Address To` put your second account address, any amount of Eth you want to send in the `Amount (Eth)` field.

The `Keyword (Gif)` field will retrieve from Giphy (using your api key)  a Gif using your keyword. And Finally you can send a `message`.

You are now ready to click `Send Now` and you should see your message appear at the bottom of the `Latest transactions`.
