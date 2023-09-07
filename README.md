# This Code to complete Swisstronik Challenge on LearnWeb3

1. Install Hardhat
```
npm install --save-dev hardhat
```
2.  Create a Hardhat project
```
npx hardhat
```
3. Press enter on Create a JavaScript project
```
888    888                      888 888               888
888    888                      888 888               888
888    888                      888 888               888
8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
888    888 .d888888 888    888  888 888  888 .d888888 888
888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

Welcome to Hardhat v2.17.1

? What do you want to do? …
▸ Create a JavaScript project
  Create a TypeScript project
  Create an empty hardhat.config.js
  Quit
```
4. Make sure you install the hardhat toolbox
```
npm install --save-dev @nomicfoundation/hardhat-toolbox
``` 
5. After edit .sol -> compile
```
npx hardhat compile
```
6. Function Deploy
```
npx hardhat run scripts/deploy.js --network swisstronik
```
7. Try to interact with your deployer contract
! Edit your deployed contract and execute this command below !
```
npx hardhat run scripts/setMessage.js --network swisstronik
```
```
npx hardhat run scripts/getMessage.js --network swisstronik
```


Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
