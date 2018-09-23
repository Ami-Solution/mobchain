#Advanced Mobility Infrastructure Sharing

## AMIS Transportation
This is a project done during the BIOTS2018 Hackathon. The aim of AMIS is to offer a decentralized transportation system touching ground sea air market sharing places.

The following is included in the repository:

* doc:            documentation
* example_webui:  An example of web interface 
* homepage:       The web interface of Amis Mobility project
* src:            Source code of the AMIS Transportation project
* video:          Screen cast of homepage usage

Go to [https://ami-solution.github.io/transportation/homepage/](https://ami-solution.github.io/transportation/homepage/) to interact with the currently deployed contracts on the Ropsten test network. Make sure you have installed the MetaMask browser plugin and have selected the Ropsten test network.

### User Interface
Create new user: Add your name and transportation type, click "Add User", and confirm transaction. You will be rewarded 250 MOB Tokens.
Request Car: Select start and end location and the transportion type. Currently only two lenders, one with a EV and one with one with a regular terrestrial transportation system; could be bus, car, bike, motorcycle, horse...

### Testing the ropsten contract
https://ropsten.etherscan.io/address/0x695812015959805765a768bFC81DEC406F1ae625  

### Deploying the contracts using remix
1. Clone repository
2. In MetaMask, select the Ropsten test network and ensure you have some funds in your wallet
3. Open http://remix.ethereum.org/ and add the contracts in src/contracts
4. Select the "run" tab and chose the environment "injected web3"
5. Click "create" and confirm transaction when MetaMask popup comes up
6. Click on the "mobcoin" button to read out the mobcoin address to show your MOB balance in MetaMask.
