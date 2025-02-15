
# Treasure Hunt

## Overview

Treasure Hunt is a blockchain-based game built on the **Aptos** network, leveraging **Move** smart contracts and a **Next.js** frontend. Players explore a decentralized world, find treasures, and earn rewards using smart contract interactions.

## Features

-   **Smart Contracts on Aptos**: Move-based contracts handle treasure logic, rewards, and ownership.
    
-   **Next.js Frontend**: A responsive and interactive UI for players to participate in the hunt.
    
-   **On-Chain Rewards**: Earn tokens or NFTs by discovering hidden treasures.
    
-   **Decentralized Gameplay**: Fully on-chain game mechanics ensuring transparency and fairness.
    
-   **Wallet Integration**: Connect and play using an Aptos-compatible wallet.
    

## Technologies Used

-   **Blockchain**: Aptos
    
-   **Smart Contracts**: Move
    
-   **Frontend**: Next.js, React
    
-   **Backend**: Node.js (if applicable)
    
-   **Wallet Integration**: Aptos Wallet SDK
    

## Installation & Setup

### Prerequisites

-   Node.js (>= 16.x)
    
-   Yarn or npm
    
-   Aptos CLI & Move compiler
    

### Backend (Move Smart Contracts)

1.  Install Aptos CLI:
    
    ```
    curl -sSf https://aptos.dev/install.sh | bash
    ```
    
2.  Navigate to the contract folder:
    
    ```
    cd contracts
    ```
    
3.  Compile and deploy contracts:
    
    ```
    aptos move compile
    aptos move publish --profile default
    ```
    

### Frontend (Next.js)

1.  Clone the repository:
    
    ```
    git clone https://github.com/quy475574/treasure-hunt.git
    cd treasure-hunt
    ```
    
2.  Install dependencies:
    
    ```
    npm install  # or yarn install
    ```
    
3.  Run the development server:
    
    ```
    npm run dev  # or yarn dev
    ```
    
4.  Open http://localhost:3000 in your browser.
    

## Usage

1.  Connect your Aptos-compatible wallet.
    
2.  Explore the map and search for treasures.
    
3.  When a treasure is found, interact with the smart contract to claim rewards.
    
4.  Monitor your collected items and rewards on your profile.
    

## Smart Contract Overview

The game utilizes Move modules to:

-   Mint and manage in-game assets.
    
-   Handle reward distribution.
    
-   Verify user ownership of discovered treasures.
    

## Contribution

Contributions are welcome! Follow these steps:

1.  Fork the repository.
    
2.  Create a new branch (`feature/your-feature`).
    
3.  Commit your changes.
    
4.  Push to your fork and submit a pull request.
    

## License

This project is licensed under the MIT License.
