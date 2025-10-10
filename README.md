<h1 align="center">🎮 MMIDOUGame Auto Play Tool</h1>

<p align="center">
  <b>Automated Mytel MyID Game Player — Termux Edition</b><br>
  🧠 Built in Python • 💎 Collect Rewards • 🔐 License Protected
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-green?logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Stable-brightgreen"/>
  <img src="https://img.shields.io/badge/License-Protected-red"/>
</p>

---

## 🚀 Features

✅ **Auto-Play Ou Game** (World Mode)  
💎 **Auto Collect Rewards** after each wave  
🔐 **License Key + HWID Protection**  
📡 **Stable WebSocket Game Connection**  
📱 100% **Termux Compatible**  
🌈 **Colorful & Clean Logs** for easy tracking  
💬 Supports both English & Myanmar users  

---

## ⚙️ Installation Guide (Termux / Linux)

> 🪄 Quick setup in just a few commands!

```bash
# 1️⃣ Update your environment
pkg update -y && pkg upgrade -y

# 2️⃣ Install Python & Git
pkg install python git -y

# 3️⃣ Clone the repository
git clone https://github.com/AdAM-GHOST/mmidougame.git
cd mmidougame

# 4️⃣ Install Python dependencies
pip install asyncio requests websockets pycryptodome
chmod +x mmidou

# 5️⃣ Run the script
./mmidou
