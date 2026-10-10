# Delta-Neutral MM Bot

A high-frequency delta-neutral bot written in Rust that maintains a SOL hedge between a Meteora DLMM position and a perpetual short on Lighter DEX.I

## Quickstart

### 1. Clone repository
```bash
git clone https://github.com/TrinityWeb3/Deltra-neutral-hedge-bot.git
cd Deltra-neutral-hedge-bot
```

### 2. Configuration

Create a `.env` file in the root of the project with the following variables:

```env
METEORA_POOL_ADDRESS=your meteora pda address
METEORA_WALLET_ADDRESS=Your sol address
```
Lighter -> Tools -> Api Keys<br>

![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image_1.png)<br>

And then "Generate API Key"<br>

![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image2.jpg)<br>

```
LIGHTER_API_URL=https://mainnet.zklighter.elliot.ai
LIGHTER_ACCOUNT_INDEX=your account id
LIGHTER_MARKET_ID=2 (SOL), # see official lighter API Docs 

LIGHTER_API_KEY_INDEX=your API's index
LIGHTER_API_KEY=your Lighter API
LIGHTER_API_SECRET=your Lighter secret api
```

### 3. Useful links

<a href="https://apidocs.lighter.xyz/docs/get-started" target="_blank">Official Lighter API</a>



### 3. Usefull links<br>

Official Lighter API - https://apidocs.lighter.xyz/docs/get-started{:target="_blank"}

