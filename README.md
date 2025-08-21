# ⚡ Cryptonex – Next-Gen Crypto Trading Platform  

🔗 **Live Demo:** [cryptonex-frontend.vercel.app](https://cryptonex-frontend.vercel.app/)  

---

## 🔥 What is Cryptonex?  

Cryptonex is a **full-stack web application** that brings together:  
- Real-time **cryptocurrency trading**  
- **AI-driven insights** with live market data  
- Secure **wallet & payments**  
- Enterprise-grade **authentication & 2FA**  

Built with **React + Spring Boot**, Cryptonex showcases how fintech apps can be both **user-friendly** and **secure at scale**.  

---

## ✨ Core Capabilities  

- 🤖 **AI Assistant** – Query crypto prices, trends, and stats (Gemini + CoinGecko APIs)  
- 💹 **Trading & Portfolio** – Buy/sell coins, auto-update balances, and visualize performance  
- 💳 **Wallet Ops** – Send, receive, withdraw to bank, top-up via Razorpay/Stripe  
- 🔐 **Security First** – Spring Security, OTP-based 2FA, email verification  
- 🛠 **Admin Tools** – Approve/reject user withdrawal requests  

---

## 🛠 Tech Stack  

| Layer         | Tools & Frameworks                                           |
|---------------|--------------------------------------------------------------|
| **Frontend**  | React, Tailwind, Redux, Axios, React Router, Shadcn UI       |
| **Backend**   | Java, Spring Boot, MySQL, Spring Security, Java Mail Sender  |
| **Payments**  | Razorpay, Stripe                                             |
| **APIs**      | Gemini API, CoinGecko API                                    |
| **Hosting**   | Vercel (Frontend), Cloud/Local Server (Backend)              |

---

## 🏗 Architecture Diagram

```
[ React Frontend ] <---- Axios ----> [ Spring Boot API ] <----> [ MySQL DB ]
        |                                    |
        ↓                                    ↓
 [ Gemini API / CoinGecko API ]       [ Payment Gateways ]
```

---
## 📂 Core Features

### 💬 AI Chatbot – "Crypto Assistant"

* Handles natural crypto-related queries like *"BTC price today"*
* Fetches market data & historical trends instantly
* Powered by Gemini & CoinGecko APIs

### 📊 Trading & Portfolio

* Buy & Sell interface with live rates
* Performance tracking with visual stats
* Auto-refreshing portfolio balances

### 💳 Wallet & Payments

* Secure wallet-to-wallet transfers
* Withdraw to bank accounts
* Add balance using Razorpay or Stripe

### 🔐 Authentication & Security

* Login/Register via **Spring Security**
* 2FA using OTP verification
* Forgot Password flow with email link

---

## 🚀 Quick Start

### 1️⃣ Clone the repository

```bash
git clone https://github.com/shivam-jondhale/CryptoNex
```

### 2️⃣ Backend Setup

```bash
cd Cryptonex-Backend-master
mvn clean install
mvn spring-boot:run
```

* Update `application.properties` with:

  * MySQL credentials
  * API keys for Gemini & CoinGecko
  * Razorpay & Stripe keys

### 3️⃣ Frontend Setup

```bash
cd Cryptonex-Frontend-main
npm install
npm run dev
```

* Add `.env` file with:

  * Backend API URL
  * Payment gateway keys

---


## 🛠 Challenges Solved

* **Real-Time Data Handling:** Optimized API calls to refresh prices without overloading APIs.
* **State Management:** Used Redux to sync data between trading, wallet, and portfolio modules.
* **Payment Reliability:** Built a dual-gateway payment system to ensure uptime.
* **Security:** Enforced 2FA for sensitive wallet and bank transactions.

---
