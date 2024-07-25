# Contract Deploy On Swisstronic Testnet with Hardhat

This project demonstrates a basic Hardhat use case on Swisstronik Testnet. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Create file .env
```Copy This
PRIVATE_KEY=YOUR_PIVATE_KEY
```

!!! Keep your Private key secret and becarefull for ripper or scammer !!!

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```
https://github.com/Kadafimuamar/Swisstronik_testnet
