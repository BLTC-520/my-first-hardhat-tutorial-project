## My first Hardhat project with BoilerPlate 

Screenshot of work:
![image](https://github.com/user-attachments/assets/3e4bacf6-6ad4-45a4-9ffa-b9206d349ce1)

To run this repo locally: 
- git clone this repo
- create and .env file and also to set up your Alchemy_API_KEY and also use a burner wallet as we need also the SEPOLIA_PRIVATE_KEY (then "source.env")
- npm install
- npx hardhat node

Go to a new terminal 
- npx hardhat run scripts/deploy.js --network sepolia

- cd frontend
- npm install
- npm start
  
Open http://localhost:3000/ to see your Dapp. You will need to have Coinbase Wallet or Metamask installed and listening to localhost 8545.

For more information: https://github.com/NomicFoundation/hardhat-boilerplate
