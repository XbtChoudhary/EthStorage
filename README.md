<div align="center">

# 🛠 EthStorage V1 Trusted Setup Ceremony  

<img src="https://github.com/user-attachments/assets/69640371-df60-4f83-9b86-cb7216d9ee28" alt="EthStorage Ceremony Banner" width="800"/>

---

</div>

## 📜 Overview
The **EthStorage V1 Trusted Setup Ceremony** is a collaborative effort to generate **zk-SNARK parameters** for EthStorage circuits.  
By contributing, you’re helping to:

- 🔒 Strengthen security by preventing parameter manipulation  
- 🌐 Support decentralization with a large contributor base  
- 🔍 Maintain transparency through a fully auditable process  

> 📅 **Event Window**: **August 13, 2025 – August 22, 2025**

---

## 📋 Participation Requirements

| Requirement      | Details |
|------------------|---------|
| **OS**           | Linux (recommended), macOS, or Windows with WSL2 |
| **GitHub**       | Account ≥ 1 month old, ≥ 1 public repo, ≥ 5 follows, ≥ 1 follower, Gist read/write access |
| **Internet**     | Stable, good upload speed |
| **Dependencies** | Node.js ≥ 18, npm ≥ 9.2.0 (via NVM recommended) |

---

## 🚀 Step-by-Step Guide (Linux)

### **1️⃣ Update & Install Required Tools**
```bash
sudo apt-get update && sudo apt-get upgrade -y
```
```bash
sudo apt install curl screen iptables build-essential git wget lz4 jq make gcc nano \
automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev \
tar clang bsdmainutils ncdu unzip libleveldb-dev ca-certificates -y
```

### **2️⃣ Install NVM & Node.js (Required for Ceremony CLI)**

```bash
# Download and install NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# Install Node.js v18
nvm install 18
nvm use 18

# Set Node.js v18 as default
nvm alias default 18

# Reload shell configuration
source ~/.bashrc
```
<img width="1213" height="265" alt="Screenshot 2025-08-14 231457" src="https://github.com/user-attachments/assets/ef7054df-c0cd-4408-a5f9-0f352d245972" />

### **3️⃣ Create and Navigate into Directory**
```bash
mkdir ceremony && cd ceremony
```
**Install NPM Package**
```bash
npm install -g @p0tion/phase2cli
```

### **4️⃣ Authenticate with GitHub**
Run the following command to start the authentication process:
```bash
phase2cli auth
```
⬩ Authenticate Github and copy the code from terminal

⬩ Paste code on Github page

⬩ Check back terminal to confirm you're IN.

<img width="1189" height="318" alt="Screenshot 2025-08-14 231552" src="https://github.com/user-attachments/assets/4c10e256-fa91-4362-87ac-1915b7f8518a" />

### **5️⃣ Open a Screen Session**
Create a new `screen` session to run the ceremony:
```bash
screen -S ceremony
```
**Contribute to the Ceremony**
```bash
phase2cli contribute
```
⬩ Use the arrow keys to select EthStorage V1 Trusted Setup Ceremony.

⬩ Press Enter to continue.

⬩ Press Enter again to use the Random selection for entropy.

⬩ Wait for your turn to contribute.

<img width="1393" height="310" alt="Screenshot 2025-08-14 230900" src="https://github.com/user-attachments/assets/0c716015-312e-4f48-8ff1-cf983aa3cf25" />

---





