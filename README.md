# Lynxia

**Lynxia** is a system for monitoring the exposure of personal and sensitive data on the web.

Initially developed for personal use, Lynxia collects mentions of names, emails, CPFs, and other user-defined data, storing the results locally and sending alerts when new occurrences are found.

---

## 🛠 Main Features

- Monitoring mentions of personal data on the web.
- Local storage of searches in a SQLite or PostgreSQL database.
- Alerts via email or Telegram when new mentions are found.
- Execution logs to track search history.
- Simple configuration for personal use or client testing.

---

## 💻 Technologies Used

- **Python**: main language for monitoring scripts.
- **SQLite / PostgreSQL**: database for storing results.
- **Flask / FastAPI (optional)**: simple web interface. - **Cron (Linux/Armbian)**: scheduling periodic tasks.
- **Telegram Bot API / SMTP**: sending alerts.

---

## ⚙️ Project Structure

```text
/lynxia
├─ src/ # Python scripts (collection, analysis, alerts)
├─ data/ # Database or CSV files
├─ logs/ # Execution logs
├─ config/ # Email, Telegram, etc. settings
└─ README.md # This file
