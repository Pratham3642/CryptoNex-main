# ⚡ Cryptonex – AI-Powered Crypto Trading Platform  

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Frontend](https://img.shields.io/badge/Frontend-React-blue)](https://cryptonex-frontend.vercel.app)  
[![Backend](https://img.shields.io/badge/Backend-SpringBoot-orange)](#)  
[![Status](https://img.shields.io/badge/Status-Production--Ready-success)](#)  

🔗 **Live App:** [cryptonex-frontend.vercel.app](https://cryptonex-frontend.vercel.app)  

---

## 📌 Overview  
Cryptonex is a **full-stack cryptocurrency trading platform** that replicates real-world crypto trading with **AI insights** and **bank-grade security**.  

- 🌍 End-to-end **scalable architecture** (React + Spring Boot + MySQL)  
- 🤖 Integrated **AI-powered chatbot** for live crypto queries  
- 💳 Secure payments with **Razorpay & Stripe**  
- 🔐 Authentication with **2FA & OTP**  

---

## ✨ Features  

- **AI Chatbot (Crypto Assistant)**  
  Query live prices (BTC, ETH, etc.) using **Gemini & CoinGecko APIs**  

- **Trading & Portfolio**  
  Buy/sell with live rates, real-time portfolio tracking, and performance analytics  

- **Wallet & Payments**  
  - Wallet-to-wallet transfers  
  - Bank withdrawals  
  - Balance top-up via Razorpay/Stripe  

- **Authentication & Security**  
  - Login/Register with Spring Security  
  - OTP-based 2FA  
  - Forgot password recovery  

---

## 🖥 Tech Stack  

**Frontend** → React, Tailwind CSS, Redux, Axios, React Router DOM, Shadcn UI  
**Backend** → Java, Spring Boot, MySQL, Spring Security, Java Mail Sender  
**Payments** → Razorpay, Stripe  
**APIs** → Gemini API, CoinGecko API  
**Deployment** → Vercel (Frontend), Local/Cloud (Backend)  

---

## 🏗 Architecture  

```txt
[ React Frontend ] <---- Axios ----> [ Spring Boot API ] <----> [ MySQL DB ]
        |                                    |
        ↓                                    ↓
 [ Gemini API / CoinGecko API ]       [ Payment Gateways ]
