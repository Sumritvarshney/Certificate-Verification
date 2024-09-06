# Certificate DApp

The **Certificate DApp** is a decentralized application that allows the issuance and verification of certificates securely on the blockchain. This DApp leverages **Ethereum** blockchain technology and **smart contracts** to ensure the integrity and authenticity of issued certificates. Built using **React** for the frontend and **Solidity** for the smart contract, this project ensures that certificate data remains tamper-proof and accessible to everyone.

## ✨ Features

- **Issue Certificates:** Only the admin account (who deployed the smart contract) can issue new certificates by connecting to MetaMask.
- **View Certificates:** Anyone can view issued certificates by connecting their MetaMask wallet.
- **Blockchain Storage:** All certificate details are stored on the blockchain, ensuring they are secure, immutable, and verifiable.
- **MetaMask Integration:** Connect your MetaMask wallet to interact with the DApp. Ensure you're on the correct network to interact with the deployed smart contract.

## 🚀 Getting Started

To get the Certificate DApp up and running on your local machine, follow these steps:

### Prerequisites

Ensure you have **Node.js** and **MetaMask** installed.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/akhilkailas017/Certificate-dApp.git
   cd certificate-dapp
   ```

2. **Install the dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

4. **Connect MetaMask:**
   - Open MetaMask in your browser.
   - Connect to the correct network where the smart contract is deployed.

5. **Done!** Now you can start issuing and viewing certificates on the blockchain.

## 🔗 Connecting to MetaMask

- Before issuing or viewing certificates, make sure to connect your MetaMask wallet.
- Only the **admin account** (the account that deployed the smart contract) can issue certificates.
- Any connected user can view the issued certificates.

## 📜 Smart Contract Details

- **Technology Used:** React, Solidity
- **Smart Contract Deployment:** Deployed using Hardhat Ignition.
- **Smart Contract ABI and Address:** Already integrated within the DApp for seamless interaction.

## 👤 Admin Access

- The account that deploys the smart contract becomes the **admin**. This account has exclusive rights to issue certificates.
- Ensure that your MetaMask wallet is connected to the admin account to access the certificate issuance page.

## 🛠️ Tech Stack

- **Frontend:** React.js
- **Blockchain:** Ethereum
- **Smart Contract Language:** Solidity
- **Smart Contract Deployment:** Hardhat Ignition
- **Wallet Integration:** MetaMask

## 📝 Usage

1. **Issue Certificate:**
   - Navigate to the "Issue Certificate" page.
   - Ensure you're connected to MetaMask as the admin.
   - Fill in the certificate details and click "Issue".

2. **View Certificate:**
   - Navigate to the "View Certificate" page.
   - Connect to MetaMask with any account.
   - Enter the certificate ID to view its details on the blockchain.

## 📧 Contact

For any questions or issues, please contact [akhilkailas2001@gmail.com](mailto:akhilkailas2001@gmail.com).

## 📜 License

This project is licensed under the MIT License.
