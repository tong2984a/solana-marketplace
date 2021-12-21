# Steps to run webapp
$ git clone https://github.com/thuglabs/create-dapp-solana-nextjs.git solana-marketplace

$ cd solana-marketplace

$ node version
> v16.10.0

$ yarn

$ yarn run dev

# Configurations
src/config/candy-machine.config.js includes the following configuration:
- REACT_APP_CANDY_MACHINE_CONFIG
- REACT_APP_CANDY_MACHINE_ID
- REACT_APP_TREASURY_ADDRESS
- REACT_APP_CANDY_START_DATE
- REACT_APP_SOLANA_NETWORK
- REACT_APP_SOLANA_RPC_HOST

src/pages/_app.tsx file includes the following configurations:
- SOLANA_NETWORK = WalletAdapterNetwork.Devnet;

src/views/CandyMachineMintView/config.ts includes the following configurations:
- REACT_APP_CANDY_MACHINE_CONFIG=
- REACT_APP_CANDY_MACHINE_ID=
- REACT_APP_TREASURY_ADDRESS=
- REACT_APP_CANDY_START_DATE=

