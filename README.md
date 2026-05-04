# Medusa Active Threat Defense - SBI Finnovation Hackathon

## 🛡️ Overview
Medusa is a proactive, on-device AI security layer designed to protect users—especially the elderly—from social engineering, phishing, and voice scams. This interactive demo showcases how Medusa's on-device ML intercepts threats in real-time before a compromise occurs.

---

## 🚀 Key Features

### 1. Device Simulation & UX
* **Interactive Phone Mockup:** Realistic mobile interface simulation.
* **Multi-State Screens:** Includes Sleep, Lock, and Home screen transitions.
* **Dynamic Status Bar:** Live clock and system status icons (Wi-Fi, Signal, Battery).
* **Premium Design System:** Glassmorphism effects, modern typography (Inter), and sleek color palettes.
* **Dark Mode Support:** Full system-wide theme switching (Light/Dark).

### 2. Core Security Features (Medusa Guard)
* **Trusted SBI Contacts:** A cryptographically verified registry of official bank helpline numbers.
* **Loved Ones Network:** A linked guardian protocol that notifies family members of intercepted threats.
* **On-Device AI Monitor:** Real-time status indicator for the local Machine Learning classifier.
* **App Permission Scan:** Automated monitoring for suspicious behavior in installed applications.

### 3. Communication Interface
* **Native Call Log:** Categorized call history (Trusted, Blocked Scam, Telemarketer).
* **Interactive Dialer:** Functional T9-style dialer overlay for manual calls.
* **Messages App:** SMS/WhatsApp interface showing legitimate and blocked phishing attempts.

### 4. AI Threat Detection & Interception
* **Automated Presentation Flow:** Programmed sequence demonstrating end-to-end protection.
* **Notification Interception:** Real-time blocking of suspicious incoming message notifications.
* **Live Transcription:** NLP-driven voice-to-text conversion during active calls.
* **Social Engineering Detection:** AI analysis of call content for scam patterns.
* **Threat Probability Meter:** Visual "Suspicion Meter" escalating based on live call analysis.

### 5. Reporting & Community Defense
* **Multi-Channel Reporting:** Integrated buttons to report to Loved Ones, SBI, and Cyber Cell.
* **Community Defense Stats:** Educational banners showing collective protection impact.

---

## 🗺️ Application Menu Map

```text
[INITIAL STATES]
├── Sleep Screen (Tap to wake)
└── Lock Screen (Swipe/Tap to unlock)

[MAIN APPLICATION]
├── GUARD TAB (Medusa Dashboard)
│   ├── Trusted SBI Contacts ──────► [Sub-Page: Contacts List]
│   ├── Loved Ones ────────────────► [Sub-Page: Guardian List]
│   ├── On-Device AI Status
│   └── App Permission Scan
│
├── CALL TAB (Recent Calls)
│   ├── Community Defense Banner
│   ├── Call Logs (Trusted/Blocked/Missed)
│   └── Floating Dialer Button ────► [Overlay: Dialpad]
│
└── MESSAGE TAB (Inbox)
    ├── Legitimate Messages
    └── Blocked Phishing Attempts (Medusa Protected)

[INTERACTIVE COMPONENTS]
├── Incoming Call Screen ──────────► [Active Call with Transcription]
└── Medusa Intercept Sheet ────────► [Emergency Block & Reporting]
```

---

## ✅ TODO List
- [ ] Implement real-time ML model integration (moving beyond simulation).
- [ ] Expand the Trusted SBI Contacts registry via official API.
- [ ] Hardened security for the "Loved Ones" notification protocol.
- [ ] Add multi-language support for live voice transcription (Hindi, Bengali, etc.).
- [ ] Direct integration with the National Cyber Crime Reporting Portal API.
- [ ] Biometric lock for the Medusa Guard settings.

---

## 🛠️ Technology Stack
* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript.
* **Icons:** FontAwesome 6.4.0.
* **Typography:** Inter (Google Fonts).
* **Animations:** Custom CSS3 keyframes and transitions.
