Certificate DApp
The Certificate DApp is a decentralized application that provides a secure, transparent, and tamper-proof way to issue and verify certificates on the Ethereum blockchain. By leveraging smart contracts, this DApp guarantees the integrity and authenticity of certificates, eliminating fraud and manual verification bottlenecks. The frontend is built with React.js, and the smart contract is implemented using Solidity.

✨ Features
Issue Certificates: Exclusively the admin account (smart contract deployer) can issue certificates via MetaMask.

Verify Certificates: Anyone can verify issued certificates by connecting their MetaMask wallet.

Immutable Storage: All certificate data is stored permanently on the blockchain, ensuring security and transparency.

MetaMask Integration: Seamlessly connect with MetaMask to interact with the DApp and ensure engagement with the correct Ethereum network.

🚀 Getting Started
Prerequisites
Node.js installed

MetaMask installed and configured

Preferred Ethereum smart contract deployment tool (Remix, Hardhat, Truffle, etc.)

Deployment
Deploy the Cert.sol smart contract located in the contracts folder using your preferred method.

Copy the contract ABI (from the compiled Cert.json) to the src/scdata/Cert.json file.

Paste the deployed contract address into src/scdata/deployed_addresses.json.

Installation and Running

bash
git clone https://github.com/SumritVarshney/Certificate-Verification.git 
<br>
cd Certificate-DApp
<br>
npm install
<br>
npm run dev
<br>
Open the app in your browser and connect your MetaMask wallet on the network where the contract is deployed.

Admin users can now issue certificates; others can verify them instantly.

🔗 MetaMask Connection
Only the admin account can issue certificates.

Any user can verify certificates after connecting their wallet.

🛠️ Tech Stack
Frontend: React.js

Blockchain: Ethereum

Smart Contract: Solidity

Wallet: MetaMask

👤 Admin Access
The connecting wallet that deploys the smart contract is the admin with exclusive issuance rights.

📜 License
This project is licensed under the MIT License.

📧 Contact
For help or questions, contact varshneysumrit@gmail.com.
