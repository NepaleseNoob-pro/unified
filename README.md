<div align="center">

<!-- Animated Header Banner -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00F0FF&center=true&vCenter=true&width=800&height=70&lines=%F0%9F%9A%80+UNIFIED+AUTONOMOUS+SUPER-AGENT;%E2%9A%A1+Multi-Provider+LLM+Engine+(Gemini+%2B+Groq+%2B+Agnes);%F0%9F%94%91+Dynamic+API+Rotation+(Unlimited+Keys);%F0%9F%94%92+Bytecode+XOR+Cipher+Protected;%F0%9F%91%B7%E2%80%8D%E2%99%82%EF%B8%8F+Created+by+Rupesh+Kumar+Mahato" alt="Typing Header" />

# 🚀 UNIFIED AUTONOMOUS SUPER-AGENT v4.0

### *The Ultimate AI Agentic Engine with Multi-Provider Failover, Mandatory Verification Gates & Bytecode XOR Protection*

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Platform Termux](https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-00599C?style=for-the-badge&logo=android&logoColor=white)](#-installation--quick-start)
[![Code Security](https://img.shields.io/badge/Code%20Security-XOR%20Bytecode%20Encrypted-red?style=for-the-badge&logo=securityScorecard&logoColor=white)](#-code-protection--encryption)
[![Multi-Provider](https://img.shields.io/badge/AI%20Providers-Gemini%20%7C%20Groq%20%7C%20Agnes-FF6F00?style=for-the-badge&logo=googleai&logoColor=white)](#-multi-provider-llm-engine)
[![License MIT](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)](LICENSE)
[![Status Active](https://img.shields.io/badge/Status-Production%20Ready-00E676?style=for-the-badge)](https://github.com/rupeshmahato)

</div>

---

## 📌 Table of Contents
- [✨ Key Features](#-key-features)
- [🔒 Code Protection & Encryption](#-code-protection--encryption)
- [🔑 Dynamic API Key Manager (`/api` & `/newapi`)](#-dynamic-api-key-manager-api--newapi)
- [⚡ Multi-Provider LLM Engine](#-multi-provider-llm-engine)
- [📥 Installation & Quick Start](#-installation--quick-start)
- [🎮 CLI Slash Commands](#-cli-slash-commands)
- [🛡️ Security & Git Compliance](#️-security--git-compliance)
- [👑 Creator & Developer Profile](#-creator--developer-profile)

---

## ✨ Key Features

- **🔒 Code Protection & Anti-Theft**: Main runtime (`unified_agent.py`) is obfuscated and encrypted with bytecode XOR cipher protection to prevent source code theft.
- **🔑 Unlimited API Key Support**: Add 1 to 1000+ API keys dynamically using `/api` or `/newapi` commands!
- **⚡ 4-Tier Multi-Provider Rotation**: Automatic failover across Groq (~0.12s speed), Agnes AI, Google Gemini Direct API, and Custom endpoints.
- **🛡️ Mandatory Verification Gates**: Ensures code modification is verified before declaring task completion.
- **📝 Visual Colored Diffs**: Unified git-like colored diffs when updating files.
- **🎯 Hierarchical Planning**: Built-in plan manager tracking complex tasks step-by-step.
- **🌐 Cross-Platform Ready**: Works natively on Termux (Android), Linux, Ubuntu, and Windows (PowerShell/CMD).

---

## 🔒 Code Protection & Encryption

This project employs **Multi-Layer Bytecode XOR Cipher Encryption** to protect intellectual property:
1. **Compilation**: Source code is pre-compiled into optimized Python bytecode objects (`marshal`).
2. **Compression**: Bytecode is compressed using Zlib Level 9 maximum compression.
3. **Multi-Pass XOR Cipher**: Compressed binary is encrypted using a proprietary multi-round XOR key transformation.
4. **Base64 Payload Execution**: Execution wrapper decrypts bytecode dynamically in memory during runtime without saving raw Python files to disk.

---

## 🔑 Dynamic API Key Manager (`/api` & `/newapi`)

The system allows users to configure as many API keys as needed (**1000+ keys supported** with zero hardcoded limits!).

### How to Add API Keys Interactively:

Inside the interactive agent CLI prompt (`➜ UNIFIED >`), simply type:

```bash
/api
```
*or*
```bash
/newapi
```

This launches the **Interactive Dynamic API Key Manager**:

```text
🔑 ================= DYNAMIC API KEY MANAGER ================= 🔑
 Choose API Provider to Add (Supports 1 to 1000+ API keys):
 1. 🤖 Gemini API Key  (Direct Google Gemini AI key)
 2. ⚡ Groq API Key    (Groq Cloud Llama / GPT key)
 3. 🌸 Agnes AI Key    (Agnes API Hub key)
 4. 🔧 Custom Entry    (format: provider:key:model:url)
 5. 📋 List Status     (Check active API key count)
 0. ❌ Exit / Done
 -------------------------------------------------------------
➜ Select Option (0-5):
```

### Quick Inline API Addition Commands:
```bash
/api gemini AIzaSyYourGoogleGeminiKeyHere
/api groq gsk_YourGroqCloudKeyHere
/api agnes sk-YourAgnesAIKeyHere
/listapi
```

---

## ⚡ Multi-Provider LLM Engine

| Priority | Provider | Model | Latency / Fallback |
| :---: | :--- | :--- | :--- |
| **Tier 1** | ⚡ **Groq Cloud** | `openai/gpt-oss-120b` | Ultra-fast sub-second execution (~0.12s) |
| **Tier 2** | 🌸 **Agnes AI Hub** | `agnes-2.5-flash` | High-concurrency failover endpoint |
| **Tier 3** | 🤖 **Google Gemini Direct** | `gemini-2.5-flash` | Direct Google REST API integration |
| **Tier 4** | 🔧 **Custom Endpoints** | Custom OpenAI-compatible | Custom model routing |

---

## 📥 Installation & Quick Start

### 1️⃣ Clone Repository
```bash
git clone https://github.com/rupeshmahato/unified.git
cd unified
```

### 2️⃣ Run Unified Super-Agent
```bash
python3 unified_agent.py
```

### 3️⃣ Add Your API Key
When prompted, type `/api` or `/newapi` and enter your Gemini, Groq, or Agnes API key!

---

## 🎮 CLI Slash Commands

| Slash Command | Description |
| :--- | :--- |
| `/api` or `/newapi` | Launches interactive API Key Manager menu to add unlimited keys. |
| `/listapi` or `/statusapi` | Shows current status & count of active keys across providers. |
| `/clear` or `/reset` | Clears conversation context and resets active task plan. |
| `quit` or `exit` | Gracefully closes the agent session. |

---

## 🛡️ Security & Git Compliance

- 🔒 **Zero Hardcoded Secrets**: All personal credentials, API keys, and access tokens have been completely sanitized.
- 🛡️ **`.gitignore` Integration**: Automatically excludes `unified_agent_raw.py`, `build_protected.py`, `api.json`, `apis.txt`, `.env`, logs, and temporary caches from git commits.

---

<div align="center">

## 👑 Creator & Developer Profile

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=700&size=24&pause=1000&color=FFD700&center=true&vCenter=true&width=700&height=50&lines=Created+%26+Maintained+by+Rupesh+Kumar+Mahato;Full-Stack+Developer+%26+Automation+Engineer;Janakpur+%2F+Dhanusha%2C+Nepal" alt="Creator Header" />

### **Rupesh Kumar Mahato**
*Lead Architect, Software Engineer & Creator of Unified Autonomous Super-Agent*

📍 **Address / Location**:  
**Bharatpur (Dhanusha), Ward No. 3, Ganeshman Charnath Municipality, Madhesh Province, Nepal**

---

### 🌐 Connect & Contact Links

[![Website](https://img.shields.io/badge/Website-rupeshkumarmahato.com.np-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rupeshkumarmahato.com.np)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B977%209809642422-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/9779809642422)
[![Telegram](https://img.shields.io/badge/Telegram-%40Rupesh22784-0088cc?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Rupesh22784)
[![Gmail](https://img.shields.io/badge/Email-rupesh54321kumar%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rupesh54321kumar@gmail.com)
[![Facebook](https://img.shields.io/badge/Facebook-Rupesh%20Mahato-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=61578964559888)
[![YouTube Channel](https://img.shields.io/badge/YouTube-18%20Puraan%20Channel-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@18_puraan?si=h9PH0POSunLGSXka)

---

### 💼 Products & Projects Developed
- 🏫 **VIPERP / School Management Software**: Integrated ERP solution hosted at [rupeshkumarmahato.com.np](https://rupeshkumarmahato.com.np)
- 🤖 **Autonomous Multi-Channel Media Bots**: Automated content generators and publishers across YouTube, Facebook, and Dailymotion.
- ⚡ **Unified Agentic AI Systems**: Standalone high-speed agentic automation tools for mobile & server infrastructure.

</div>

---

<div align="center">
⭐ <i>If you find this project useful, please star this repository on GitHub!</i> ⭐
</div>
