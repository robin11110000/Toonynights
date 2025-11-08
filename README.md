

# 🩵 ToonyNights — Webtoon NFT Platform on Somnia Network

A **modern, web3-enabled digital comic platform** built with **Next.js** and **Thirdweb**, running locally on the **Somnia blockchain testnet**.
Browse webtoons, read episodes, purchase premium content, and mint NFTs — all powered by blockchain.

## 🌟 Features

* **Browse & Discover:** View trending and popular webtoons
* **Read Episodes:** Smooth infinite scroll reader with lazy-loaded images
* **Web3 Wallet:** Connect your MetaMask wallet on Somnia testnet
* **Premium Episodes:** Pay-per-episode model via blockchain transactions
* **Creator Dashboard:** (coming soon) Upload webtoons and mint NFTs
* **Dark Mode:** Clean and comfortable reading experience

---

## 🧩 Tech Stack

| Category                | Technology                           |
| ----------------------- | ------------------------------------ |
| **Frontend**            | Next.js 16, React 19, TypeScript     |
| **Styling**             | Tailwind CSS v4, Radix UI            |
| **Web3 SDK**            | Thirdweb v5                          |
| **Blockchain**          | Somnia Network (Testnet)             |
| **Local Dev**           | Node.js 18+, npm                     |
| **Future Integrations** | Supabase (DB), Vercel Blob (Storage) |

---

## ⚙️ Getting Started

### Prerequisites

* Node.js 18+
* npm (or yarn)
* MetaMask wallet extension
* Thirdweb account and Client ID

---

### Installation Steps

1. **Clone the repository**

   ```bash
   git clone <https://github.com/robin11110000/Toonynights>
   cd toonynights
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Create a `.env.local` file**

   ```env
   NEXT_PUBLIC_THIRDWEB_CLIENT_ID=your_thirdweb_client_id
   ```

   > Only Thirdweb Client ID is required for this local version.

4. **Run the local development server**

   ```bash
   npm run dev
   ```

5. **Open in your browser**

   ```
   http://localhost:3000
   ```

---

## 🧠 Environment Variables

| Variable                         | Description                       | Required |
| -------------------------------- | --------------------------------- | -------- |
| `NEXT_PUBLIC_THIRDWEB_CLIENT_ID` | Your Thirdweb dashboard Client ID | ✅ Yes    |

**To get a Client ID:**
Go to [Thirdweb Dashboard → API Keys](https://thirdweb.com/dashboard).

---

## 🧭 Usage Guide

### 📖 Browsing Webtoons

* Home page shows trending and popular series
* Use filters and categories (mock data currently)

### 💳 Purchasing Premium Episodes

* Connect MetaMask → Somnia testnet
* Click "Unlock" to initiate a transaction
* Confirm transaction in wallet
* Access episode instantly after confirmation

### 🧑‍🎨 Creator Dashboard

(Under development — placeholder UI active)

* Will allow uploading, minting, and viewing NFT statistics

---

## 🪙 Somnia Network Configuration

| Field        | Value                                                                  |
| ------------ | ---------------------------------------------------------------------- |
| **Chain ID** | 50311                                                                  |
| **RPC URL**  | [https://dream-rpc.somnia.network/](https://dream-rpc.somnia.network/) |
| **Token**    | STT (Somnia Test Token)                                                |
| **Explorer** | [Somnia Testnet Explorer](https://explorer.testnet.somnia.network/)    |

> 🪄 Get free STT from the [Somnia Faucet](https://explorer.testnet.somnia.network/faucet).

---

## 🧰 Build and Run (Production)

```bash
npm run build
npm start
```

Runs the app in optimized production mode (still local).

---
<img width="1900" height="880" alt="image" src="https://github.com/user-attachments/assets/18f85193-f358-4666-bf1e-12d62dbb99e5" />
---

## 🚀 Future Roadmap

* Cross-chain support (Polygon / Ethereum)
* Comment & rating system
* Reader analytics and progress tracking
* Mobile-friendly UI

---

