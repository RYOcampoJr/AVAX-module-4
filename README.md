After cloning the GitHub repository, follow these steps to get the code running on your computer:

1. Install Dependencies:** Inside the project directory, in the terminal, install dependencies using npm:
  npm install
2. Open Additional Terminals: Open two additional terminals within your VS Code environment.
3. Start Local Ethereum Node: In the second terminal, start a local Ethereum node using Hardhat:
   npx hardhat node
This command initializes a local Ethereum network on your machine.

4. Deploy the Smart Contract: In the third terminal, deploy the smart contract to your local network:
    npx hardhat run --network localhost scripts/deploy.js
Ensure that the deployment script (scripts/deploy.js) is correctly configured to deploy your Solidity smart contract.

6. Explore the DApp: Connect your MetaMask wallet to interact with the DApp on the local Ethereum network. You can manage the message, update the favorite number, and explore dynamic message length functionalities.
By following these steps, you can set up, deploy, and run the decentralized application locally on your machine.

## Interacting with the Contract
### 1. View Current Message and Favorite Number:
➝ Connect your MetaMask wallet.  
➝ The DApp will display the current message and favorite number automatically.  

### 2. Update the Message:
➝ Enter a new message in the input field.  
➝ Click "Update Message" and confirm the transaction in MetaMask.  

### 3. Update the Favorite Number:
➝ Enter a new favorite number in the input field.  
➝ Click "Update Favorite Number" and confirm the transaction in MetaMask.    

### 4. Set Message Length:
➝ Enter a new maximum length for the message in the input field.  
➝ Click "Set Message Length" and confirm the transaction in MetaMask.  

