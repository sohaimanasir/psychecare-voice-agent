# 🧠 PsycheCare Clinic — AI Voice Agent

> An AI-powered appointment booking voice agent built with **Retell AI** for PsycheCare Clinic, Karachi, Pakistan.

---

## 🎙️ Meet Sara

**Sara** is an intelligent voice agent that answers inbound calls for PsycheCare Clinic and books patient appointments automatically — no human receptionist needed.

She can:
- 🗣️ Speak in **English** or switch to **Urdu/English mix**
- 📅 Book appointments with **4 doctors**
- 📋 Collect patient name, preferred doctor, date, time & contact number
- ✅ Confirm all details before ending the call
- 📊 Auto-extract booking data after every call

---

## 🏥 Clinic Details

| Detail | Info |
|--------|------|
| Clinic | PsycheCare Clinic |
| Speciality | Psychiatry |
| Location | Karachi, Pakistan |
| Working Days | Monday – Saturday |
| Working Hours | 10:00 AM – 7:00 PM |

---

## 👨‍⚕️ Available Doctors

| Doctor | Available Days |
|--------|---------------|
| Dr. Umaima | Monday, Wednesday, Friday |
| Dr. Farooq | Tuesday, Thursday, Saturday |
| Dr. Azam | Monday, Tuesday, Wednesday |
| Dr. Maliha | Thursday, Friday, Saturday |

---

## 🤖 Tech Stack

| Component | Technology |
|-----------|-----------|
| Platform | [Retell AI](https://retellai.com) |
| AI Model | GPT-4.1 (OpenAI) |
| Agent Type | Single Prompt Agent |
| Voice | Retell-Della (Sara) |
| Vocabulary | Medical |
| Post-Call Analysis | GPT-4.1 |

---

## 📞 How Sara Works (Call Flow)

```
📲 Caller dials the number
        ↓
👋 Sara greets: "Hello! Thank you for calling PsycheCare Clinic..."
        ↓
📝 Collects: Full Name
        ↓
🩺 Asks: Preferred Doctor
        ↓
📅 Confirms: Doctor's available days → Preferred Date
        ↓
🕐 Asks: Preferred Time (10AM - 7PM)
        ↓
📱 Collects: Contact Number
        ↓
✅ Repeats all details back for confirmation
        ↓
🙏 Confirms booking & ends call warmly
```

---

## 🧠 Sara's Prompt

```
You are Sara, a booking assistant for PsycheCare
Clinic, Karachi. Book psychiatry appointments.

DOCTORS & AVAILABILITY:
- Dr. Umaima: Mon, Wed, Fri
- Dr. Farooq: Tue, Thu, Sat
- Dr. Azam: Mon, Tue, Wed
- Dr. Maliha: Thu, Fri, Sat

HOURS: Mon-Sat, 10AM-7PM

STEPS:
1. Greet & introduce yourself
2. Get caller's full name
3. Ask preferred doctor (suggest Dr. Umaima if unsure)
4. Confirm doctor's available days, get preferred date
5. Get preferred time (10AM-7PM)
6. Get contact number
7. Repeat: Name, Doctor, Date, Time, Phone
8. Confirm & end warmly

RULES:
- Speak English; switch to Urdu mix if caller does
- Never ask about medical condition
- Fees: "Our team will confirm on arrival"
- Be calm, gentle, non-judgmental
- Keep responses short
```

---

## 📊 Post-Call Data Extracted Automatically

After every call, Retell AI extracts:

- ✅ Patient Name
- ✅ Doctor Chosen
- ✅ Appointment Date
- ✅ Appointment Time
- ✅ Caller Phone Number
- ✅ Call Summary
- ✅ Call Successful (Yes/No)
- ✅ User Sentiment

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `README.md` | This file — project overview |
| `PsycheCare_BRD.docx` | Business Requirements Document |
| `agent_config.json` | Retell AI agent configuration (exported) |

---

## 🚀 Future Improvements

- [ ] Google Calendar integration for real-time availability
- [ ] SMS confirmation after booking
- [ ] CRM integration for patient records
- [ ] Full Urdu language support
- [ ] Outbound reminder calls
- [ ] Website widget so patients can call Sara online

---

## 👤 Author

**Sohaima**
Built as a beginner AI project using Retell AI
📍 Karachi, Pakistan
📅 April 2026

---

## 📄 License

This project is for educational and portfolio purposes.

---

> *"Making mental health care more accessible — one call at a time."* 🧠💙
