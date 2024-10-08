# EVM Auto Transfer
### Installation
1. Clone the repository:
```bash
git clone https://github.com/dante4rt/evm-auto-transfer.git
cd evm-auto-transfer
```
2. Install the necessary packages:
```bash
npm install
```
### Configuration
1. Define the Chains:
```bash
   rm chains/testnet.json && nano chains/testnet.json
```
- Edit file `testnet.json` as in the code below. (Ctrl + X, Y and Enter will do to save).    
```bash
[
  {
    "name": "Movement MEVM",
    "rpcUrl": "https://mevm.devnet.imola.movementlabs.xyz",
    "chainId": "30732",
    "symbol": "MOVE",
    "explorer": "https://explorer.devnet.imola.movementlabs.xyz"
  },
  {
    "name": "Sonic Fantom Testnet",
    "rpcUrl": "https://rpc.testnet.soniclabs.com",
    "chainId": "64165",
    "symbol": "S",
    "explorer": "https://testnet.soniclabs.com"
  },
  {
    "name": "Berachain bArtio",
    "rpcUrl": "https://bartio.rpc.berachain.com",
    "chainId": "80084",
    "symbol": "BERA",
    "explorer": "https://bartio.beratrail.io"
  },
  {
    "name": "Plume Testnet",
    "rpcUrl": "https://testnet-rpc.plumenetwork.xyz/http",
    "chainId": "161221135",
    "symbol": "ETH",
    "explorer": "https://testnet-explorer.plumenetwork.xyz"
  },
  {
    "name": "Unit Zero Testnet",
    "rpcUrl": "https://rpc-testnet.unit0.dev",
    "chainId": "88817",
    "symbol": "UNIT0",
    "explorer": "https://explorer-testnet.unit0.dev"
  },
  {
    "name": "StratoVM Sepolia Testnet",
    "rpcUrl": "https://rpc.stratovm.io",
    "chainId": "93747",
    "symbol": "SVM",
    "explorer": "https://explorer.stratovm.io"
  },
  {
    "name": "Story Testnet",
    "rpcUrl": "https://testnet.storyrpc.io",
    "chainId": "1513",
    "symbol": "IP",
    "explorer": "https://testnet.storyscan.xyz"
  },
  {
    "name": "Minato",
    "rpcUrl": "https://rpc.minato.soneium.org/",
    "chainId": "1946",
    "symbol": "ETH",
    "explorer": "https://explorer-testnet.soneium.org"
  },
  {
    "name": "Swisstronik Testnet",
    "rpcUrl": "https://json-rpc.testnet.swisstronik.com/",
    "chainId": "1291",
    "symbol": "SWTR",
    "explorer": "https://explorer-evm.testnet.swisstronik.com/"
  },
  {
    "name": "Hemi Testnet",
    "rpcUrl": "https://testnet.rpc.hemi.network/rpc",
    "chainId": "743111",
    "symbol": "ETH",
    "explorer": "https://testnet.explorer.hemi.xyz"
  },
  {
    "name": "Curtis",
    "rpcUrl": "https://curtis.rpc.caldera.xyz/http",
    "chainId": "33111",
    "symbol": "APE",
    "explorer": "https://curtis.explorer.caldera.xyz"
  }
]
```

2. Define Private Keys:
```bash
nano privateKeys.json
```
- Edit file `privateKeys.json` as in the code below. (Ctrl + X, Y and Enter will do to save).
```bash
   [
      "0xYOUR_PRIVATE_KEY"
   ]
```
3. Start transfer:
```bash
npm start
```

