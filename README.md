# 💊 Smart Medicine Reminder Automation

An AI-powered no-code medicine reminder system built using n8n, Telegram, and Google Sheets to help users remember their medicines on time and reduce missed doses.

---

# 🚀 Overview

This project automates medicine reminders using scheduled workflows in n8n.  
Users can store medicine details and timings in Google Sheets, and the system automatically sends reminders through Telegram at the correct time.

If the user does not confirm taking the medicine, the system sends a follow-up reminder after a short delay.

The project demonstrates:
- No-code workflow automation
- AI-assisted messaging
- Scheduling and notification systems
- Real-world healthcare utility

---

# ✨ Features

- ⏰ Scheduled medicine reminders
- 📩 Telegram notifications
- 🔁 Automatic follow-up reminders
- 📊 Medicine status tracking
- 🤖 AI-generated reminder messages
- 📋 Google Sheets integration
- ⚡ Fully automated using n8n

---

# 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| n8n | Workflow automation |
| Telegram Bot API | Sending reminders |
| Google Sheets | Medicine data storage |
| OpenAI API (optional) | AI-generated messages |

---

# ⚙️ Workflow Architecture

```text
Google Sheets
      ↓
Cron Trigger (n8n)
      ↓
Check Medicine Time
      ↓
Send Telegram Reminder
      ↓
Wait for Confirmation
      ↓
If No Response
      ↓
Send Follow-up Reminder
```

---

# 📂 Project Structure

```text
smart-medicine-reminder/
│
├── workflow.json
├── README.md
├── screenshots/
│   ├── workflow.png
│   ├── telegram-demo.png
│   └── sheets-data.png
└── docs/
    └── architecture.png
```

---

# 🔧 Setup Instructions

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/smart-medicine-reminder.git
cd smart-medicine-reminder
```

---

## 2️⃣ Setup Telegram Bot

Create a bot using BotFather:

https://telegram.me/BotFather

Copy the generated bot token.

---

## 3️⃣ Configure Google Sheets

Create a sheet with columns:

| Name | Medicine | Time | Status |
|---|---|---|---|

Example:

| John | Vitamin D | 08:00 AM | Pending |

---

## 4️⃣ Import Workflow into n8n

Open n8n and:
- Import `workflow.json`
- Add credentials
- Activate workflow

---

# 🤖 AI Usage

AI was used to:
- Generate personalized reminder messages
- Improve notification tone and clarity
- Assist in workflow planning and optimization

The workflow logic, scheduling, integrations, and automation implementation were built manually in n8n.

---

# 📸 Screenshots

## n8n Workflow
_Add screenshot here_

## Telegram Reminder
_Add screenshot here_

## Google Sheets Database
_Add screenshot here_

---

# 🌍 Use Cases

- Elderly patient medicine reminders
- Daily vitamin tracking
- Busy student medication management
- Family healthcare monitoring

---

# 🔒 Limitations

- Requires internet connection
- Depends on manual confirmation
- No direct health app integration yet

---

# 🚀 Future Improvements

- WhatsApp integration
- Voice reminders
- Mobile app dashboard
- Smart wearable integration
- Analytics for missed doses

---

# 📜 License

This project is licensed under the MIT License.

---

# 🙌 Acknowledgements

- n8n
- Telegram Bot API
- Google Sheets API
- OpenAI

---

# ⭐ Demo

_Add your live demo link here_

Example:
```text
https://t.me/YourBotName
```

---

# 👨‍💻 Author

Your Name  
GitHub: @your-github-username
