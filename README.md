# IDVault — Decentralized Identity & Credential Verification

🚀 IDVault is a **Fully On-Chain Decentralized Identity (DID) & Credential Verification system** built on Internet Computer (ICP) with cross-chain support.  
It empowers users to own, verify, and share credentials without relying on centralized authorities.

---

## ✨ Features
- ✅ Decentralized Identity creation (DID standard)
- 🔐 Zero-Knowledge Proof (ZKP) based credential verification
- 🌐 Cross-chain interoperability (ICP + Ethereum)
- 🛡️ Tamper-proof storage of credentials on-chain
- 🎓 Real-world use cases: KYC, Education certificates, Healthcare records

---

## 🏗️ Architecture
![Architecture](./docs/architecture.png)

**Workflow:**
1. User registers & gets a DID.
2. Credentials are issued and stored on ICP canisters.
3. Verifiers check credentials using ZKPs.
4. Cross-chain bridges enable multi-network usage.

---

## 🛠️ Tech Stack
- **Blockchain**: Internet Computer (Motoko/Rust), Ethereum (Solidity)
- **Frontend**: React + Tailwind + shadcn/ui
- **Backend**: Node.js (optional API gateway)
- **Storage**: ICP canisters
- **ZKP**: Circom / SnarkJS

---

## 🚀 Setup & Installation

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/IDVault.git
cd IDVault
