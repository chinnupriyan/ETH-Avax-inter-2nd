# ETH-PROOF Intermediate Starter with Next.js and Hardhat

Welcome to the ETH-PROOF Intermediate Starter kit, a robust setup for Ethereum decentralized application (DApp) development using Next.js for the front-end and Hardhat for smart contract development. This template includes a basic Solidity contract and a React-based front-end setup leveraging ethers.js for blockchain interaction.

## Getting Started

Follow these steps to set up the project on your local environment:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. **Navigate to Project Directory:**

    ```bash
    cd your-repo
    ```

3. **Install Dependencies:**

    ```bash
    npm install
    ```

4. **Prepare Your Environment:**

    - Open multiple terminals in your integrated development environment.

5. **Launch a Local Ethereum Node:**

    Start a local Hardhat node in one of the terminals:

    ```bash
    npx hardhat node
    ```

6. **Deploy Contracts to Local Network:**

    Deploy your smart contract to the local network:

    ```bash
    npx hardhat run --network localhost scripts/deploy.js
    ```

7. **Start the Front-end Application:**

    Launch your Next.js application in development mode:

    ```bash
    npm run dev
    ```

8. **View Your DApp:**

    Open your browser and go to [http://localhost:3000/](http://localhost:3000/) to interact with your decentralized application.

## Project Structure

- **`contracts/`**: Contains the Solidity smart contract files.
- **`artifacts/`**: Compiled contract artifacts are stored here.
- **`scripts/`**: Houses deployment scripts for the smart contracts.
- **`frontend/`**: Includes the Next.js and React codebase for the DApp's front-end.
- **`hardhat.config.js`**: Configuration file for Hardhat.
- **`next.config.js`**: Configuration file for Next.js.
- **`package.json`**: Lists project dependencies and scripts.
- **`README.md`**: Documentation for the project.

This starter kit provides a flexible foundation for building Ethereum DApps, tailored for intermediate developers looking to explore blockchain development with modern tools.

## Additional Notes

- Ensure you have Node.js and npm installed on your system.
- MetaMask extension is recommended for interacting with Ethereum wallets in the browser.
- chinuupriyan
-METACRAFTERS ID:-chinnupriyan

