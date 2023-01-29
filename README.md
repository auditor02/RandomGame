# Random card game Hack

In this game, a card is pciked at random and users try to guess it's value. The user who guss correctly gets 0.1 ether. However, since the randomness is generated on chain, it can be predicted.

This project demonstrates that using an onchain to generate random vaues isn't reliable. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
# RandomGame
