# MedicareAI

MedicareAI is a digital assistant for consultant doctors that helps manage
appointments, patient bookings, and advance payments via M-Pesa, with
WhatsApp Business notifications.

The system is designed to run as a mobile application (Android & iOS)
backed by a secure backend service.

The system acts like a virtual front desk — available 24/7 — reducing missed appointments and admin workload.

---

## 🚀 Features

- 📅 Appointment booking via WhatsApp
- 🩺 Service selection (consultation types)
- 💰 Advance payment via M-PESA STK Push
- ✅ Automatic payment confirmation
- 🧠 AI intent detection (appointments, availability, busy, general inquiries)
- 📊 Google Sheets as a free database
- 🧩 Built with Make.com (no-code / low-code)

---

## 🏥 Target Users

- Consultant doctors
- Private clinics
- Specialist practices
- Medical centers using WhatsApp Business

---

## 🧠 Architecture Overview

- **WhatsApp Business Account (WABA)** — Patient communication
- **Make.com** — Workflow automation
- **Google Gemini** — Intent detection & AI responses
- **Google Sheets** — Appointments, services, payments
- **Safaricom M-PESA API** — STK Push payments

---

## 🔐 Security & Privacy

- No patient data stored in code
- API keys stored in Make.com secrets
- Google Sheets access restricted
- Designed for HIPAA-aware workflows (implementation dependent)

---

## 🛠 Setup Summary

1. Connect WhatsApp Business API
2. Configure Gemini AI modules
3. Set up Google Sheets database
4. Configure M-PESA STK Push
5. Test appointment & payment flow

## 🔐 Security & Configuration

Sensitive credentials (M-Pesa keys, WhatsApp tokens, API secrets) are NOT
stored in this repository.

See `backend/.env.example` for required environment variables.

---

## 📌 Status

🟢 Active development  
🟢 Core booking flow working  
🟡 Payment automation in progress

---

## 📄 License

MIT License
