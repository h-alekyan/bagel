# Bagel - Instant ERC-20 Crypto Exchange

Simple instant ERC-20 exchange between ETH and BGL and vice versa.

## Features:
- Connect MetaMask or other wallet
- Identicon w/ public key
- Buy ETH with BGL
- Buy BGL with ETH
- Custom inputs
- Automated conversion calculation



## Dependencies:
Node.js: https://nodejs.org/en/ <br>
Ganache (to play around): https://www.trufflesuite.com/ganache <br>
Truffle: https://www.trufflesuite.com/ <br>
Metamask or any other common wallet.


## Running
1. Make sure all dependencies are installed
2. run
`npm install`
3. Open the command prompt, go to the directory of the project and run `truffle migrate`
4. In the project terminal, run `npm run start`


## Testing
1. Make sure truffle migration has been done properly
2. Open the command prompt, go to the direcory of the project and run  `truffle test`

If you want to run transactions from the command line itself, use `truffle console`. 
Feel free to play around with the code, but make sure to run `truffle migrate --reset` every time.



