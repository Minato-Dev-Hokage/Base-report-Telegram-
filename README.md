<div align="center">
  <img src="https://img.icons8.com/color/96/000000/telegram-app.png" alt="Telegram Bot"/>
  <h1>🤖 REPORT BOT</h1>
  
  <img src="https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram"/>
  <img src="https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js"/>
  <img src="https://img.shields.io/badge/Gmail-Email-EA4335?style=for-the-badge&logo=gmail"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  
  <h3>🚀 Send emails directly from Telegram</h3>
</div>

---

## 📋 Table of Contents
- [Prerequisites](#prerequisites)
- [⚠️ Important Warnings](#️-important-warnings)
- [Bot Setup - Telegram](#-bot-setup---telegram)
- [Gmail Setup - App Password](#-gmail-setup---app-password)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Commands](#-commands)
- [Deployment](#-deployment)
- [Screenshots](#-screenshots)
- [FAQ](#-faq)
- [License](#-license)

---

## ✅ Prerequisites

| Requirement | Version |
|-------------|---------|
| Node.js | v16+ |
| NPM | v8+ |
| Gmail Account | Any |
| Telegram Account | Any |

---

## ⚠️ Important Warnings

> 🔴 **CRITICAL SECURITY WARNINGS**

| Risk | Consequence | Solution |
|------|-------------|----------|
| Using real Gmail password | ❌ Account compromised | Use **App Password** only |
| Sending spam to abuse@telegram.org | ❌ Bot + Gmail banned | Use for legitimate purposes only |
| Mass unsolicited emails | ❌ Legal consequences | Get consent from recipients |

<div align="center">
  <img src="https://img.shields.io/badge/⚠️-USE_REAL_PASSWORD-red?style=for-the-badge"/>
</div>

---

## 🤖 Bot Setup - Telegram

### Step 1: Create your bot with BotFather

<div align="center">
  <img src="https://img.shields.io/badge/1️⃣-Go_to_@BotFather-26A5E4?style=flat-square&logo=telegram"/>
</div>

1. Open Telegram and search for [**@BotFather**](https://t.me/BotFather)
2. Send the command: `/newbot`
3. Choose a **name** for your bot (e.g., `NTED Report Bot`)
4. Choose a **username** for your bot (e.g., `@NtedReportBot` - must end with `bot`)
5. ✅ **COPY the TOKEN** - looks like: `7234567890:AAGkFJkfjfkdjfkdjfkjdf`

<div align="center">
  <img src="https://files.catbox.moe/l0f0vs.jpg" alt="BotFather Example" width="400"/>
  <br/>
  <i>Example of BotFather token generation</i>
</div>

---

## 📧 Gmail Setup - App Password

> 🔴 **USE YOUR REAL GMAIL PASSWORD OR ISN'T WORKING**
> 
> <img src="https://img.shields.io/badge/⚠️-REAL_PASSWORD_WILL_WORK-red?style=flat-square"/>

### How to get an App Password:

<div align="center">
  <img src="https://img.shields.io/badge/2️⃣-Enable_2FA_First-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/3️⃣-Get_App_Password-green?style=flat-square"/>
</div>

#### Step-by-step:

| Step | Action |
|------|--------|
| 1 | Go to [Google Account Security](https://myaccount.google.com/security) |
| 2 | Enable **2-Step Verification** (2FA) |
| 3 | Go to [App Passwords](https://myaccount.google.com/apppasswords) |
| 4 | Select **Mail** as the app |
| 5 | Select **Other** as the device and name it "Telegram Bot" |
| 6 | Click **GENERATE** |
| 7 | 📋 **COPY the 16-character password** (e.g., `abcd efgh ijkl mnop`) |

<div align="center"> 
  <br/>
  <i>Click GENERATE and copy your App Password</i>
</div>

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/Minato-Dev-Hokage/Base-report-Telegram.git
cd Base-report-Telegram

# Install dependencies
npm install

# Start the bot
npm start
