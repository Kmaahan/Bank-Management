# 💰 Bank Management System

A blockchain-based Bank Management System built to ensure secure, transparent, and tamper-proof banking operations. This project utilizes **smart contracts**, **Node.js**, and **Express.js** to simulate real-world banking tasks such as account creation, balance checks, and secure transactions on a decentralized network.

---

## 🚀 Features

- 🏦 **Account Creation** – Register new users with secure credentials
- 💸 **Deposit & Withdraw** – Simulate safe financial transactions
- 🔐 **Blockchain Integration** – Every transaction is logged immutably
- 📊 **Transaction History** – View transaction logs with timestamps
- ⚙️ **Smart Contract Backend** – All banking logic handled by Ethereum smart contracts
- 🌐 **Web Interface (Optional)** – Easy-to-use UI (if integrated)

---

## 🧠 Tech Stack

| Layer         | Tech Used            |
|---------------|----------------------|
| 🧾 Smart Contract | Solidity, Hardhat          |
| 🔙 Backend      | Node.js, Express.js         |
| 🔗 Blockchain   | Ethereum (Local: Ganache)   |
| 📡 Interaction  | web3.js / ethers.js         |
| 🧪 Testing      | Mocha, Chai, Hardhat Tests  |

---

## 📦 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Kmaahan/Bank-Management.git
cd Bank-Management

# Install dependencies
npm install

# Compile and deploy contracts locally (using Hardhat)
npx hardhat compile
npx hardhat node  # runs local blockchain
npx hardhat run scripts/deploy.js --network localhost

# Start the server
node index.js
  
