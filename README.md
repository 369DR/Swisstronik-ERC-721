# swisstronik-ERC-721

This project sets up a Hardhat environment to deploy and interact with an ERC-721 (NFT) contract on the Swisstronik testnet. Follow the steps below to get started.

## Prerequisites

Ensure you have the following installed:
- Node.js
- npm

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/369DR/Swisstronik-ERC-721.git
    cd Swisstronik-ERC-721
    ```

2. Make the setup script executable and run it:
    ```sh
    chmod +x erc721.sh
    ./erc721.sh
    ```

3. Follow the prompts to enter your private key and NFT details.

## Deployment

The script will:
- Install necessary dependencies.
- Create a Hardhat project.
- Configure the Hardhat environment.
- Create and compile an ERC-721 contract.
- Deploy the contract to the Swisstronik testnet.
- Mint an NFT using the deployed contract.

## Notes

- The contract address will be saved in `contract.txt`.
- The transaction hash for the minting process will be printed in the terminal.
