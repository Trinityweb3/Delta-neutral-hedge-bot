# Delta-Neutral MM Bot

A high-frequency delta-neutral market-making bot designed to hedge SOL price volatility while farming trading fees in Meteora DLMM pools. It automatically maintains a short position on Lighter DEX to balance the spot exposure of the LP position.

## Quickstart

### 1. Clone repository
```bash
git clone https://github.com/TrinityWeb3/Delta-neutral-hedge-bot.git
cd Deltra-neutral-hedge-bot
```

### 2. Configuration

Create a `.env` file in the root of the project with the following variables:

```env
METEORA_POOL_ADDRESS=your_meteora_pda_address_here
METEORA_WALLET_ADDRESS=your_sol_wallet_address_here
```
Lighter -> Tools -> Api Keys<br>

![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image_1.png)<br>

And then "Generate API Key"<br>

![img](https://raw.githubusercontent.com/Trinityweb3/Deltra-neutral-hedge-bot/refs/heads/main/images/image2.jpg)<br>

```
LIGHTER_API_URL=https://mainnet.zklighter.elliot.ai
LIGHTER_ACCOUNT_INDEX=your_account_id
LIGHTER_MARKET_ID=2 (SOL), # see official lighter API Docs 

LIGHTER_API_KEY_INDEX=your_API_index
LIGHTER_API_KEY=your_Lighter_API
LIGHTER_API_SECRET=your_Lighter_secret_api
```

### 3. Useful links

<a href="https://apidocs.lighter.xyz/docs/get-started" target="_blank">Official Lighter API</a>


