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

LIGHTER_API_URL=https://mainnet.zklighter.elliot.ai

![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image_1.png)
![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image2.jpg_

LIGHTER_ACCOUNT_INDEX=your account id ( Lighter -> Tools -> Api Keys -> Generate API Key
LIGHTER_MARKET_ID=2 (SOL), see here - 

LIGHTER_API_KEY_INDEX=your API's index
LIGHTER_API_KEY=your Lighter API
LIGHTER_API_SECRET=your Lighter secret api
```


