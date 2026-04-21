# 🚀 Stellar Banking Dashboard Level-1

A modern, high-performance **Stellar Testnet Wallet Dashboard** built with a premium fintech UI/UX approach. This project demonstrates seamless wallet interaction, transaction handling, and a production-grade interface design.

---

## ✨ Features

### 🔐 Wallet Integration
- **Connect & Disconnect:** Seamlessly link with the Freighter wallet.
- **Automatic Detection:** Built-in network detection for Stellar Testnet.
- **Real-time Display:** Instant wallet address visibility upon connection.

### 💰 Balance Management
- **Live Data:** Fetch real-time XLM balances via Stellar SDK.
- **Dynamic UI:** Balance cards update automatically without page refreshes.

### 💸 Transaction System
- **Secure Sending:** Transfer XLM to any valid Stellar address.
- **Validation:** Robust client-side validation for addresses and amounts.
- **Live Feedback:** Real-time success/error notifications with transaction hashes.

### 🎨 Advanced UI/UX
- **Glassmorphism:** Layered UI with frosted glass effects.
- **Visual Depth:** Subtle grid patterns and smooth animations using **Framer Motion**.
- **Fintech Aesthetic:** Clean, high-contrast black-and-white design optimized for single-screen use.

---

## 🧱 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React + Vite |
| **Styling** | Tailwind CSS |
| **Animation** | Framer Motion |
| **Icons** | Lucide React |
| **Blockchain** | Stellar SDK |
| **Wallet API** | Freighter |

---

## 📁 Project Structure

```text
stellar-wallet-app/
├── src/
│   ├── services/
│   │   ├── freighter.js   # Wallet connection logic
│   │   └── stellar.js     # Horizon server interactions
│   ├── App.jsx            # Main dashboard component
│   ├── main.jsx
│   └── index.css          # Tailwind & Global styles
├── public/
├── package.json
└── README.md
```

---

## 📸 Screenshots

<img width="1918" height="872" alt="1" src="https://github.com/user-attachments/assets/8ddef6d1-9a2c-4d8f-a992-183bd059e35a" />

<img width="1918" height="965" alt="2" src="https://github.com/user-attachments/assets/ba38c650-6c45-4702-93cf-0fcdd7bc1f98" />

<img width="1918" height="871" alt="3" src="https://github.com/user-attachments/assets/341cf01d-1361-4661-85ac-7ef2a9eeaa09" />
<img width="1917" height="965" alt="4" src="https://github.com/user-attachments/assets/1b989392-c039-42d0-87dc-7c5d9f8199b1" />

<img width="1918" height="547" alt="5" src="https://github.com/user-attachments/assets/bc4b40ca-bca7-46f7-8fe4-e3188c7b3e8f" />

<img width="1916" height="872" alt="6" src="https://github.com/user-attachments/assets/c6cc866a-90b2-4dac-bcf3-a7c734365f11" />




---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/stellar-wallet-app.git
cd stellar-wallet-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Install Required Packages *(if starting from scratch)*

```bash
npm install framer-motion lucide-react @stellar/stellar-sdk @stellar/freighter-api
```

### 4. Run the Application

```bash
npm run dev
```

---

## 🧪 Usage

1. **Connect Wallet** — Click the **Connect** button and approve the request in your Freighter browser extension.
2. **Send XLM** — Enter the recipient's public key and the amount.
3. **Approve** — Confirm the transaction in the Freighter popup.
4. **View Status** — Monitor the dashboard for the transaction hash and updated balance.

---

## 🎯 Design Philosophy

- **Micro-interactions:** Small visual cues that provide immediate feedback.
- **Typography Hierarchy:** Clear font scaling for optimal readability.
- **Security First:** No private keys are ever stored or handled by the app — all signing happens within Freighter.

---

## 🚀 Future Enhancements

- **Transaction History:** A detailed table of past activities.
- **QR Integration:** Scan to receive XLM.
- **Analytics:** Visual charts for spending/receiving trends.
- **Dark/Light Mode:** Full theme toggle support.
- **Explorer Links:** Direct links to Stellar.expert for every transaction.

---

## 🧑‍💻 Author

**Nandini Pandey**


---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🔗 Useful Links

- [Stellar Documentation](https://developers.stellar.org/)
- [Freighter Wallet](https://www.freighter.app/)
- [Stellar Explorer](https://stellar.expert/)
