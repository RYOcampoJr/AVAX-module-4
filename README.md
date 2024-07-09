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

5. Launch the Frontend: Back in the first terminal, start the Next.js development server to launch the frontend:
    npm run dev
The development server starts, and the DApp should now be accessible at http://localhost:3000.

6. Explore the DApp: Connect your MetaMask wallet to interact with the DApp on the local Ethereum network. You can manage the message, update the favorite number, and explore dynamic message length functionalities.
By following these steps, you can set up, deploy, and run the decentralized application locally on your machine.
