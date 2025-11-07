# Enclana — Encrypted Solana Layer
CA:

Welcome to **Enclana**, the privacy-focused layer for Solana.  
Enclana enables **encrypted transactions**, **commitment-based states**, and **zero-knowledge verification** —  
bringing confidentiality and integrity to Solana’s speed layer.

This project provides the foundation for developing private Solana programs and clients that  
support encrypted transfers and off-chain decryption via view keys.

---

## Introduction

The **Encrypted Solana Project (Enclana)** introduces privacy-preserving transaction tools within the Solana ecosystem.  
It focuses on encrypting balances, commitments, and transaction metadata so that values remain confidential while still  
being verifiable through zero-knowledge proofs.  

This repository is your starting point for implementing encrypted transfers, commitment sets, and proof verification  
on Solana.  

---

## Features

- 🔒 **Encrypted Transfers:** Hide amounts, memos, and balances while preserving validity.
- 🧮 **Zero-Knowledge Proofs:** Validate correctness (no inflation, correct balances) without revealing private data.
- ⚙️ **Commitment-Based Ledger:** Use commitments and nullifiers for double-spend prevention.
- 🌐 **Cross-Platform:** Compatible with Windows, macOS, and Linux.
- 🧩 **Modular Design:** Integrates with existing Solana programs and clients.

---

## Getting Started

### Prerequisites
- Rust (stable)
- Solana CLI
- Node.js 18+ and npm

### Build the Solana program
```bash
cd solana-program
cargo build --release

