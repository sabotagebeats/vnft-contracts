# The VeryNifty Smart Contracts 

## quickstart

```bash 
git clone https://github.com/sabotagebeats/vnft-contracts.git VNFT

cd VNFT
```

```bash

yarn install

```

> you might get node-gyp errors, ignore them and run:

```bash

yarn start

```

> in a second terminal window:

```bash

yarn chain

```

> in a third terminal window:

```bash

yarn compile && yarn deploy

```

🔏 Edit smart contracts like `VNFT.sol` in `packages/buidler/contracts`

📝 Edit your frontend `App.jsx` in `packages/react-app/src`

📱 Open http://localhost:3000 to see the app

## Testing the smart contracts

A set of scripts are available in  `packages/buidler/scripts`.

>Run them:
```bash

cd packages/buidler
npx builder run scripts/[NAME OF SCRIPT]].js

```

## Verifying contracts on Etherscan

```bash

npx buidler verify --network mainnet ADDRESS_OF_CONTRACT_TO_VERIFY PARAM_1 PARAM_2...

```

## 🏗 Thanks scaffold-eth!

> The starter code was forked from [scaffold-eth](https://github.com/austintgriffith/scaffold-eth) which has everything you need to get started building decentralized applications powered by smart contracts


