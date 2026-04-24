# 🚀 DeFi Exchange DApp

A **Decentralized Exchange (DEX)** built using **Next.js, Hardhat, and Solidity** that enables users to swap ETH with ERC20 tokens and manage liquidity pools on an Ethereum-based blockchain.

---

## 📌 Overview

This project demonstrates the core principles of **Decentralized Finance (DeFi)** by implementing a simplified **Automated Market Maker (AMM)** similar to Uniswap.

Users can:
- Connect their MetaMask wallet  
- Swap ETH ↔ CryptoDev Tokens  
- Add liquidity to the pool  
- Remove liquidity and receive LP tokens  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (React)  
- **Blockchain Development:** Hardhat  
- **Smart Contracts:** Solidity  
- **Web3 Library:** Ethers.js  
- **Wallet Integration:** MetaMask  

---

## ⚙️ Features

- 🔗 Wallet connection via MetaMask  
- 💰 Display ETH and ERC20 token balances  
- 🔄 Token swapping (ETH ↔ CD Tokens)  
- 💧 Add liquidity to the pool  
- ❌ Remove liquidity from the pool  
- 📊 Automated pricing using AMM model  

---

## 🧠 Working Principle

The exchange follows the **Automated Market Maker (AMM)** model:
x * y = k

Where:
- `x` = ETH reserve  
- `y` = Token reserve  
- `k` = constant  

This ensures token prices adjust dynamically based on supply and demand.

---


---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/NirajanCoder/defi-exchange-dapp.git
cd defi-exchange-dapp

2️⃣ Start Local Blockchain
cd hardhat-tutorial
npx hardhat node

3️⃣ Deploy Smart Contracts
npx hardhat run scripts/deploy.js --network localhost

4️⃣ Run Frontend
cd ../my-app
npm install
npm run dev

🔐 MetaMask Setup
Add a custom network:
RPC URL: http://127.0.0.1:8545
Chain ID: 31337
Import a Hardhat account private key

⚠️ Known Issues
MetaMask may display a "deceptive request" warning when approving tokens
This occurs due to security simulation on localhost
The application works correctly on test networks like Sepolia

📌 Conclusion

This project demonstrates:

Integration of frontend with blockchain
Smart contract interaction using Web3
Core DeFi concepts like liquidity pools and token swapping

🔗 GitHub Repository

👉 https://github.com/NirajanCoder/defi-exchange-dapp

📜 License

This project is for educational purposes.

---

# ✅ HOW TO USE (quick)

1. Go to your GitHub repo  
2. Click **README.md → Edit (✏️)**  
3. Replace everything  
4. Click **Commit changes**

---

# 🚀 OPTIONAL (to make it even better)

Add:
- Screenshot (very important for marks)
- Demo GIF (bonus)
- Star badge ⭐

---

If you want, I can:
👉 add screenshot section properly  
👉 make this README **top-tier portfolio level**  

Just tell me 👍

