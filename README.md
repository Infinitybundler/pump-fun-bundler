![image](https://github.com/user-attachments/assets/0954dd4f-54ea-44c4-96a8-4f40f24a08f2)


# Infinity Bundler - Pump.fun And Raydium 


## 🚀 Core Features  

### 🪙 Token Management  
- One-click token creation  
- Custom & pump vanity token launches  
- Automatic metadata upload to Pump.Fun  
- Clone existing token metadata for relaunching  

### 🔐 Wallet Operations  
- Generate & manage up to 20 sub-wallets  
- One-click JITO-powered wallet funding  
- Real-time balance monitoring  
- Seamless wallet importing  
- Anti-bubble map protection  
- Human transaction simulation for detection avoidance  

### 🚀 Launch Features  
- **Bundle Launch**: Create & buy tokens across dev + 20 wallets in block 0  
- **Experimental Launch + Snipe**: Create & snipe with detection bypass  
- **Snipe Only**: Bundle buy any token across multiple wallets  
- **Stagger Mode Options**:  
  - *Standard*: Delayed transactions for clean launches  
  - *Bundle + Stagger*: Initial bundle + staggered buys  

### 💰 Advanced Selling  
- **Dump All**: Simultaneous selling across all wallets in one bundle  
- **Delayed Sell**: Percentage-based selling with custom delays  
- **Single Wallet Sell**: Manage individual wallet sales  
- **Auto Sell**: Market cap targeted selling  
- **Smart Sell**: Activity-based reactive selling  
- **Select Sell**: Percentage-based selling across selected wallets  

### ⚡ Raydium Integration  
- **wSOL Management**:  
  - Bulk create wrapped SOL accounts  
  - One-click unwrap to regular SOL  
- **Trading Options**:  
  - Dump all (with/without dev wallet)  
  - Delayed selling across wallets  
  - Single wallet sell management  
  - Bundle buying post-migration  
  - Staggered buying for clean re-entry  

### 🔧 Utility Functions  
- **Token Transfer**: Selective wallet-to-wallet movement  
- **SOL Reclaim**: One-transaction return of SOL to funding wallet  
- **Intuitive CLI Interface**: Streamlined operations  

## 🛠 Setup  
1. Download and extract Bundler.zip.   
3. Modify the `.env` and `smartconfig.json` files (see below).  
4. Run `infinity-bundler.exe`.  

### `.env` Configuration  
Modify `.env` with your **private keys, RPC URLs, and other parameters** for proper functionality:  

```ini
SIGNER_PRIVATE_KEY=
DEV_ADDRESS=
FUNDER_PRIVATE_KEY=
SELLER_PRIVATE_KEY=
RPC_URL=
WS=
BLOCKENGINEURL=
JITO_TIP=
SELL_TIP=
DEVBUY=
LUT_ADDRESS=
COMPUTE_LIMIT_PRICE=
COMPUTE_UNIT_PRICE=
CUSTOM_OCP=
TARGET_MCAP=
NEXTBLOCK_ENDPOINT=  # (Optional)
NEXTBLOCK_API_KEY=  # (Optional)


