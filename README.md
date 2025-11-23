
# 🌾 **Bhoomika — Blockchain-Based Land Verification System**

*A transparent, tamper-proof, citizen-friendly approach to land ownership verification.*

---

## 📌 **Overview**

**Bhoomika** is a blockchain-powered land registry and verification platform designed to bring trust, transparency, and security to land ownership records in India.
It helps eliminate common issues like:

* Conflicting land claims
* Fake/forged documents
* Unauthorized transfers
* Lack of transparency in land approvals

The entire process — from land submission to council approval — is handled through a simple, accessible web application powered by **Aptos blockchain**.

Built in **24 hours at Hack-A-Sol 2025**, Bhoomika won the **Girls’ Track** and placed among the **top teams overall**.

---

## 🧠 **Why Bhoomika?**

Land disputes in India are extremely common — especially within families. One person claiming the entire ancestral land is something we all have seen happen.

Because once something is registered in traditional systems, reversing it becomes complicated and opaque.

**Bhoomika solves this by:**

* Making land submissions transparent
* Making approvals traceable
* Making records immutable
* Preventing a single bad actor from manipulating ownership

All on-chain. All publicly verifiable.

---

## 🏗 **How It Works**

### 🧍‍♂️ Citizen Flow

1. User logs in
2. Adds land details (district, tehsil, village, area, khasra number)
3. Uploads supporting documents (PDF/image/IPFS CID)
4. Submits land to the blockchain
5. The record appears as **Pending** in the council dashboard

### 🧑‍💼 Council Flow

1. Council members log in
2. View pending land applications
3. Approve, reject, or dispute claims
4. Approval updates are shown instantly to the user
5. Final state is stored immutably on Aptos

### 🌍 Map Integration

Land records include a **View on Map** button pointing to OpenStreetMap with the village/tehsil coordinates.

---

## 🛠 **Tech Stack**

### **Frontend**

* **React (Vite)**
* **TypeScript**
* **ShadCN/UI**
* **Tailwind CSS**

### **Blockchain / Backend**

* **Aptos Move smart contracts**
* **Aptos SDK**
* **Petra Wallet integration**
* No traditional backend — **blockchain = backend**

### **Storage**

* LocalStorage (mock DB)
* IPFS-compatible document CIDs

---

## 📦 **Features**

### ✅ Citizen Features

* Add, manage, and verify your land
* Upload documents or add IPFS CID
* View approval status
* Raise disputes
* Map link to land location
* Multi-language UI (English + Hindi)

### 🧑‍💼 Council Features

* Dashboard for pending/approved/rejected lands
* Approve/reject/dispute actions
* On-chain verification
* Local + blockchain status syncing

### 🌐 Additional

* Language toggle (Hindi/English)
* Clean, mobile-friendly UI
* Easy demo flow for hackathons

---

## 🚀 **Why Aptos?**

* **Fast (1–2s finality)**
* **Low fees (~$0.0001 per tx)**
* **Move language = safe and secure**
* **Parallel execution for scalability**
* **Formal verification for trust in critical systems**

Perfect for governance + public data use cases.

---

## 💻 **Run Locally**

```bash
git clone https://github.com/your-username/bhoomika.git
cd bhoomika
npm install
npm run dev
```

Make sure you have:

* Node.js 18+
* Petra wallet extension installed

---

## 📄 **Smart Contract**

The Move module handles:

* `submit_land`
* `approve`
* `reject`
* `dispute`
* `transfer_ownership` (optional/future scope)

Contracts live in `/contracts` folder (or update with your repo path).

---

## 🏆 **Achievements**

* 🥇 **Winner — Girls Track, Hack-A-Sol (National Level)**
* 🏅 **Top Finalist Team Overall**
* Built from scratch in under 24 hours

---


## 📢 **Future Scope**

* GPS-based location verification
* Aadhaar-linked digital signatures
* True multi-council multisig approvals
* NFT-based ownership certificates
* Full on-chain dispute workflow

---

## ⭐ **Show Support**

If you like Bhoomika, give the repo a **star ⭐** and follow the journey!


