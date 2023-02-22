commands 

 npm init -y

npm i hardhat --save -dev

 npx hardhat

 npm install --save-dev "hardhat@^2.12.7" "@nomicfoundation/hardhat-toolbox@^2.0.0"

<!-- $ npm install --save-dev "@ethersproject/providers@^5.4.7" "@nomicfoundation/hardhat-network-helpers@^1.0.0" "@nomicfoundation/hardhat-chai-matchers@^1.0.0" "@nomiclabs/hardhat-ethers@^2.0.0" "@nomiclabs/hardhat-etherscan@^3.0.0" "@types/chai@^4.2.0" "@types/mocha@>=9.1.0" "@typechain/ethers-v5@^10.1.0" "@typechain/hardhat@^6.1.2" "chai@^4.2.0" "ethers@^5.4.7" "hardhat-gas-reporter@^1.0.8" "solidity-coverage@^0.8.1" "ts-node@>=8.0.0" "typechain@^8.1.0" -->

 npm i @openzeppelin/contracts-upgradeable @openzeppelin/hardhat-upgrades @nomiclabs/hardhat-etherscan dotenv --save-dev

 npx hardhat run  scripts/deploy_pizza_v1.js --network goerli

 npx hardhat verify --network goerli 0x647F2ff2Df44E5b9904405b0B24B7c09118cd6Bc

npx hardhat run ./scripts/upgrade_pizza_v2.js

npx hardhat verify --network goerli 0xec3AEf25aa68aCb7f4FcE873c8E9784e55D21C00


```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
