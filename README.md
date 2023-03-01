# Open 3 terminals and run the following commands in each terminal

> Refer to this [https://app.stackup.dev/campaign_page/build-your-first-dapp](https://app.stackup.dev/campaign_page/build-your-first-dapp)
# Terminal 1
$ cd frontend
$ npm install
$ npm start

# Terminal 2
$ cd smart-contracts
$ npx hardhat node

# Terminal 3
$ cd smart-contracts
$ npx hardhat run scripts/deploy.js --network localhost
