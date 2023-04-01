Decentralized Voting System

Make Sure that you've Truffle and Ganache installed

1. Clone the repo: git clone https://github.com/shifaj22/Blockchain_Voting.git

2. Navigate to the folder: cd Blockchain_Voting

3. Install dependencies: npm install.

4. I have used Ganache app, make sure to download it from https://trufflesuite.com/ganache/, keep it running in the background by choosing the Quickstart Ethereum option.

5. Open the terminal and deploy the smart contract using: truffle migrate --reset. Run the BlockVoting application by using the command: npm run dev

6. To Cast Vote,

6.1 First Connect to localhost:7545 network in Metamask. You have to manually add the Ganache blockchain in networks, the chain id is 1337.

6.2 Secondly, copy one of the private key from the Ganache app and import it in the Metamask account section.

6.3 You should see 99-100 ETH in your address once you import it.

6.4 Manually connect Metamask to the cast vote page by clicking on the Not Connected option which is shown left side of your address and connect it to the website.

6.5 Once it shows connected, you can successfully cast your vote# Dvoting_system
