<p align="center">
  <img height="200" src="https://arena.colosseum.org/images/png/ascii-column-left.png">
  <img src="./all-colors.gif" alt="shilling.fun Logo" width="300" />
  <img height="200" src="https://arena.colosseum.org/images/png/ascii-column-right.png">
</p>

<h1 align="center">shilling.fun</h1>

<p align="center">
  <b>Shill for SOL. Contact & vest KOLs on-chain. "Work for your Bag" is back.
Welcome to the Attention Capital Market.</b>
</p>

## 🌐 Product in production mode

You can view a live demo here:  
👉 [https://shilling.fun](https://shilling.fun)

---

---

## 🚀 Overview

This repository serves as the **main entry point for the Solana Hackathon judges**.  
Here you’ll find an overview of the system, its architecture, and direct links to each module of the project.

The system is composed of four integrated repositories:

1. **Backend (Laravel API)** – Handles business logic, authentication, and blockchain interactions.
2. **Frontend (React + TypeScript + Vite)** – Modern, fast user interface.
3. **Infrastructure (IaC)** – Infrastructure as Code to deploy the environment on AWS.
4. **AWS Lambda (X API)** – Independent serverless module managing integration with the X (Twitter) API.

---

## 🧩 System Architecture

```
[ User ]
     │
     ▼
[ Frontend (React) ]
     │ 
     ▼
[ Backend (Laravel) ]
     |
     ▼
[ AWS Lambda (X API) ]
     │
     ▼
[ Infrastructure (IaC) – AWS deployment and configuration ]
```

---

## 📦 Project Repositories

| Component | Description | Repository |
|------------|--------------|-------------|
| 🧠 **Backend (Laravel)** | Central API with authentication, endpoints, and Solana connectivity. | [🔗 Backend Repository](https://github.com/shillingdotfun/backend) |
| 💻 **Frontend (React + TypeScript + Vite)** | UI connected to the API and Solana wallet. | [🔗 Frontend Repository](https://github.com/shillingdotfun/frontend) |
| ☁️ **Infrastructure (IaC)** | AWS deployment using Terraform/CDK. | [🔗 IaC Repository](#) |
| 🐦 **AWS Lambda (X API)** | Serverless microservice handling X (Twitter) API operations used to verify users. | [🔗 Lambda Repository](#) |

---

## ⚙️ Key Technologies

- **Blockchain:** Solana  
- **Backend:** Laravel 11, PHP 8.2, MySQL  
- **Frontend:** React, TypeScript, Vite, TailwindCSS  
- **Infrastructure:** AWS (Lambda, S3, EC2), Terraform  
- **Integrations:** X (Twitter) API, Privy, Solana and Solana Pay

---

## 💡 How It Works

1. The user connects with their **Solana wallet** (e.g., Phantom).  
2. From the frontend, they can list active campaigns and raids, create campaigns and raids, join them and earn money shilling.  
3. The backend processes the action and records the operation on Solana and the whole app.  

---

## 🧠 Team & Purpose

This project was developed for the **Colosseum Hackathon 2025**.

> Built by [@bruno_iykyk](https://x.com/bruno_iykyk) and [@DavidRounders](https://x.com/DavidRounders)

---

<p align="center">
  ✨ Built with passion for the <b>Colosseum Hackathon 2025</b> ✨
</p>
