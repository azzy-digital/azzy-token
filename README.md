Azzy Token (AZK)

Azzy Token is a custom ERC-20 token built with Solidity and OpenZeppelin. This project was developed as part of my journey into blockchain development and smart contract engineering.

About the Project

Azzy Token demonstrates the implementation of an ERC-20 smart contract with additional administrative and token management features.

Features

- ERC-20 standard functionality
- Initial supply of 1,000,000 AZK
- Token transfers
- Owner-only minting
- Token burning
- Emergency pause and unpause functionality
- Access control using OpenZeppelin Ownable

Technologies Used

- Solidity
- Foundry
- OpenZeppelin Contracts
- Remix IDE
- MetaMask
- Sepolia Testnet

Smart Contract Details

Detail| Information
Token Name| Azzy Token
Symbol| AZK
Initial Supply| 1,000,000 AZK
Decimals| 18
Network| Sepolia Testnet
Compiler Version| Solidity ^0.8.20

Deployment Information

Contract Address:

"0x06372C5a7C246FdAa25770C977759f13642C6bb5"

Transaction Hash:

"0x5af31c672a832ebcccf94732a49b0bfe5b7863a63fa063090b9712aaef065c80"

Testing

The smart contract was tested using Foundry.

Seven tests passed, covering:

- Initial token supply
- Token transfers
- Owner-only minting
- Unauthorized minting prevention
- Pause functionality
- Unpause functionality
- Token burning

Run Locally

Clone the repository:

git clone YOUR_GITHUB_REPOSITORY_URL

Navigate into the project:

cd azzy-token

Install dependencies:

forge install

Build the project:

forge build

Run tests:

forge test

Format Solidity files:

forge fmt

What I Learned

Building Azzy Token helped me understand ERC-20 token standards, smart contract inheritance, access control, testing with Foundry, and deploying smart contracts to a testnet.

This project represents another step in my journey as an aspiring blockchain developer.

Built with curiosity, patience, and consistency.
