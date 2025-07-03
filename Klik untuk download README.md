# CromaChain Developer Docs

Welcome to the official developer documentation for **CromaChain** – a modular Layer 2 blockchain optimized for scalability, security, and AI-native tools.

---

## 🔗 Overview

- **Website:** [https://cromachain.com](https://cromachain.com)
- **RPC Endpoint:** `https://rpc.cromachain.com` *(Beta)*
- **Explorer:** Coming Soon (Q2 2026)
- **Status:** Public Testnet Beta

---

## 🧠 Core Modules

- **zkEVM Layer** – Privacy and scalability via STARK-based proving.
- **DAG Scheduler** – Parallelized transaction execution.
- **EigenDA Integration** – High-throughput data availability.
- **AI Builder** – Zero-code smart contract & dApp generation.

---

## 🧭 Getting Started

### Connect to Testnet

```bash
network_name="CromaChain Testnet"
rpc_url="https://rpc.cromachain.com"
chain_id=93521
currency_symbol="CRM"
block_explorer="https://explorer.cromachain.com" # coming soon
```

### Add to MetaMask (manually)

1. Open MetaMask
2. Go to **Settings > Networks > Add Network**
3. Fill the form:
   - **Network Name**: CromaChain Testnet
   - **RPC URL**: `https://rpc.cromachain.com`
   - **Chain ID**: `93521`
   - **Currency Symbol**: `CRM`
   - **Block Explorer**: *(leave empty for now)*

---

## 📂 Folder Structure

```
/docs
  ├── README.md           # This file
  ├── ai-builder.md       # AI Builder module docs
  ├── dag-scheduler.md    # DAG Scheduler description
  ├── validator-guide.md  # Validator setup
  └── ...
```

---

## 📡 Validator Guide (Coming Soon)

Instructions for setting up a Croma validator will be published after public testnet phase.

---

## 🔐 Audit Status

- Phase: Initial Testnet
- Red Team: Scheduled for Q4 2025
- Target Partners: CertiK, Halborn (TBD)

---

© 2025 CromaChain
