# Auto-Message2
The library was changed to solve the problem of waiting 1 minute per person to send consecutive messages in the previous version. However, the new library does the work using the mouse and keyboard. For this reason, the screen must remain open.



# 📲 AutoMessage - WhatsApp Message Automation Tool

A Python script using PyAutoGUI to automate sending WhatsApp Web messages at a specific time, to either individual or multiple contacts.

---

## 🚀 Features

- 🕒 Automatically sends messages at a specified time
- 👤 Individual contact messaging
- 👥 Bulk (multiple) contact messaging
- 📁 JSON-based contact list management
- ⚠️ Full-screen control using mouse and keyboard simulation

---

## 🔧 Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AutoMessage.git
cd AutoMessage
```


2. Install the required libraries

```bashpip
install -r requirements.txt
```


3. Usage

```bashpip
python Auto_Message.py
```

The program will guide you:
Choose individual or bulk messaging

Add contacts if needed (first-time use)

Specify the time and message

WhatsApp Web will open, and messages will be sent automatically

⚠️ Warning: Do not use your mouse or keyboard while the script is running! PyAutoGUI controls the screen.


4. Required Files
Auto_Message.py – Main Python script

contacts.json – Contact list, created automatically

requirements.txt – Dependencies (pyautogui, webbrowser, etc.)


5.  License
MIT License – Free to use, modify, and distribute.
