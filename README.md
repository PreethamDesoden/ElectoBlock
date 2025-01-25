# ElectoBlock
A BlockChain based E-Voting Application System

ElectoBlock is a blockchain-powered e-voting system designed to ensure secure, transparent, and tamper-proof elections. It leverages Ethereum blockchain, smart contracts, and MetaMask to deliver a decentralized, efficient, and trustworthy voting experience.


### System Requirements

* Node.js (v14 or above)
* Truffle Suite
* Ganache
* MetaMask (Browser Extension)

### Features

* Secure Voter Registration: Authentication via MetaMask wallet ensures security and prevents fraud.
* Tamper-Proof Voting: Votes are recorded as blockchain transactions, ensuring immutability.
* User-Friendly Interface: Built using React.js and styled with Bootstrap for a seamless user experience.


### Tech Stack

* Front-End: React.js, Bootstrap, Web3.js
* Back-End: Solidity (Smart Contracts), Ganache (Local Blockchain)
* Tools: Truffle, MetaMask


### How It Works

- Voter Registration: Users connect their MetaMask wallet to register and authenticate.
- Voting: Voters select their candidate and confirm their vote via MetaMask.
- Transaction Confirmation: Votes are securely stored as blockchain transactions.


### How to run?

'''
cd VotingSystem
truffle compile
truffle migrate #make sure Ganache is running in the background. Navigate to Voting.json from VotingSystem dir and copy entire code and paste it in voting-system>src>conracts>Voting.json
truffle exec interact.js #Backend deployment 
'''
'''
cd voting-system
npm start #Frontend deployment
'''

### License

This project is licensed under the MIT License.


