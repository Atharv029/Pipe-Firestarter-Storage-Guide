# Pipe Firestarter Storage Guide

## Introduction
Pipe Firestarter is a decentralized storage and delivery network, like a blockchain-powered alternative to Google Drive and Cloudflare. Instead of relying on one company, it spreads files across independent nodes, making data faster, safer, and censorship-resistant.

Built on Solana, it already stores 1 petabyte of Solana’s blockchain history, cutting validator sync times by approximately 30%. Users can upload files or folders, encrypt them for privacy, and deliver content worldwide with low latency.

Payments are made in $PIPE tokens (Devnet) (1 PIPE ≈ 1 GB). When tokens are burned for storage, they are re-minted and rewarded to node operators, so the community runs the infrastructure, not corporations.

In short, Firestarter gives developers and users a full-stack decentralized alternative for storage, CDN, and edge compute at a fraction of the cost.

---

## Installation and Usage

### Step 1: Clone the repository
```bash
git clone https://github.com/Atharv029/Pipe-Firestarter-Storage-Guide && cd Pipe-Firestarter-Storage-Guide

```

### Step 2: Run the installation script
```bash
chmod +x ./Pipe_Firestarter.sh
./Pipe_Firestarter.sh
```
- If this is your first time running it, the script will install required dependencies.
- During installation, some files will open; copy the text from them and save for later use.
- Make sure to copy your **Solana public key**, as you will need it for the faucet.

### Step 3: Get Solana Devnet faucet
- Visit [Solana Faucet](https://faucet.solana.com/) to receive Solana tokens on Devnet.
- You need at least **1 SOL** to swap for PIPE tokens.

### Step 4: Run the script again
```bash
./Pipe_Firestarter.sh
```
- The main interface will appear. Follow the options in order.

---

## Main Interface Options (Alpha)

1. **Swap SOL for PIPE**
   - You must have at least 1 SOL to swap for PIPE tokens.
   - You need PIPE tokens to upload files.

2. **Upload File**
   - Provide the **full path** of the file and a **file name** to save it.
   - Only after swapping SOL for PIPE can you upload files.

3. **Check PIPE Token Usage**
   - See your PIPE token usage and rewards.

4. **Check Credentials**
   - View your saved credentials if needed.

5. **Exit Script**
   - Exit the interface safely.

---

## Notes
- first swap SOL to get PIPE, then upload files.
- Uploading more files increases your PIPE token rewards.
- Always keep a copy of your credentials and Solana public key for future use.
- This is an alpha so don't miss 
