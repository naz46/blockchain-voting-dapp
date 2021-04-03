#  Ethereum voting dapp

### Dependencies:
- [Nodejs 5.0+](https://nodejs.org/en/)
- [Truffle - 4.1.11](https://github.com/trufflesuite/truffle)
- [Ganache](http://truffleframework.com/ganache/)
- MetaMask

## Setup
```
npm install -g truffle
git clone git@github.com:naz46/blockchain-voting-dapp.git
cd blockchain-voting-dapp
npm install
npm run dev
in the other tab run 'truffle deploy --reset --network development'
```
## Important Steps
- First of all, address information must be entered as a new Ethereum network after the installation of Metamask. Address details in the truffle.js.
- An account needs to be added to the Ethereum network. This process is done with the test accounts given by Ganache so that the application can be tested. For the process of adding, it is necessary to click on the "import account" section in Figure 4.16 and enter the private key. Thus, the voting web page is never aware of your identity. Then connect the account to the web page.
- If you have any trouble stop all the servers, disconnect the account from the web page and reset the caches of the page.
 


![screen shot 2018-06-16 at 23 11 17](https://user-images.githubusercontent.com/15925608/41502169-a0c06580-71bc-11e8-80bd-b4e6cce6ffaf.png)


![screen shot 2018-06-16 at 23 10 18](https://user-images.githubusercontent.com/15925608/41502175-b70a2c86-71bc-11e8-9184-7a4df0a5e3af.png)
