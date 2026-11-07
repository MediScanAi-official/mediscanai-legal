# Privacy Policy — MediScanAI

**Effective Date:** September 7, 2026  
**Last Updated:** November 6, 2026  
**App Name:** MediScanAI – Smart Health Assistant  
**Developer:** MediScanAi (MediScanAi-official)

---

## 1. Introduction

MediScanAI ("we", "our", or "the app") is committed to protecting your personal data. This Privacy Policy explains what data we collect, how we use it, how we store it, and your rights under applicable law — including the **Digital Personal Data Protection Act, 2023 (DPDP Act)** of India.

In short:
- Your health profile, reminders, family profiles, scan history and chat history are **saved on your phone**.
- When you use an **AI feature**, what you type, say or photograph for that request — and, in some tools, parts of your health profile — **is sent over the internet to our AI provider (Anthropic Claude or Google Gemini, whichever is active)** to create the answer. See Section 3.
- We do not sell your data and we do not use it for ads.

By using MediScanAI, you agree to the practices described in this policy.

---

## 2. What Data We Collect

### 2.1 Account Data (Firebase Authentication)
- Email address
- Display name (optional)
- Profile photo URL (if signed in with Google)
- Unique Firebase User ID (UID)

This data is used **only for login/authentication purposes**.

**Guest mode:** if you use "Continue as Guest", the app creates a random anonymous Firebase ID (no email, no name) so that our AI server can tell requests apart and limit abuse. Deleting your account and data in the app (Section 8) also deletes this anonymous ID.

### 2.2 Health & Medication Data (Saved on Your Device)
- Your profile: name, age, gender, blood group, height, weight, allergies and medical conditions (all optional)
- Medicine reminders, doses marked taken or missed, and adherence history
- Family member profiles you add, and the family activity timeline
- Scan results, Dr. Chat conversations, step count and habit/water tracking

This data is saved **on your phone**. We do not keep a copy on our servers and we do not sync it between devices. **The exception is what you send to an AI feature:** when you use an AI tool, the **text you type or speak and the photos you take or choose** (prescription, lab report, medicine or food label) — and, in some tools, your age, gender, blood group, allergies, medical conditions and active medicine names — are sent over the internet, **through our server (proxy)**, to our AI provider (Anthropic Claude or Google Gemini, whichever is active). See Section 3.

### 2.3 Voice Input
- When you tap the microphone, your phone's speech-recognition service turns your speech into text. On most Android phones this is Google's speech service, not ours. We do not receive or store your voice recording.
- Depending on your phone and its settings, that service may process the audio on Google's servers rather than on the phone. The app itself never records, saves or uploads audio.
- The text is put in the box, where you can edit it. It is sent to the AI (Section 3) only when you submit it.

### 2.4 App Preferences & Settings
- Language preference
- Theme (dark/light)
- Notification settings
- First-launch status

### 2.5 Anonymous Usage & Diagnostics (Firebase Analytics, Crashlytics & Performance)
To keep the app stable and understand which features are useful, we collect **anonymous, aggregated** data via Google Firebase:
- **Crash reports & errors** (Crashlytics) — stack traces, device model, OS version, and a random app-instance ID. Tied only to your Firebase UID (or a random anonymous ID for guests), never your name or email.
- **Feature-usage events** (Analytics) — coarse counters, tagged with your Firebase UID (or a random anonymous ID for guests) and the app-instance ID, such as "a tool was opened", "a reminder was created", "a scan completed", "onboarding finished", "the upgrade screen was viewed". **We never send the content** — no medicine names, no message text, no health data, no free-form input — only the event name and a category label.
- **Performance traces** (Performance Monitoring) — app start time and network request timings.

This data is processed by Google as our data processor and is not used for advertising. If you would like this disabled for your install, contact us at the email in Section 13.

### 2.6 In-App Feedback
If you use **Profile tab → Send Feedback**, your message opens in *your own email app*. Whatever you choose to send (your message, plus the app version and device model we pre-fill to help us debug) goes directly to our support inbox by email — there is no server in between.

### 2.7 Steps from Health Connect (Optional)
- Only if you turn on **Sync steps automatically**, the app asks Android Health Connect for **read-only** access to your **step count** - nothing else, and it never writes to Health Connect.
- It reads today's total, and your daily totals for up to the last 30 days when you create a Doctor Visit Summary. Today's total is saved on your phone. Step data is not sent to our server or to the AI; it leaves your phone only inside a Doctor Visit Summary PDF that you choose to share or save.
- You can stop at any time in the app or in Health Connect settings.

---

## 3. AI Features — What Is Sent to Our AI Provider, and Why

MediScanAI's AI answers (medicine information, interactions, symptom checks, Dr. Chat, lab and prescription reading, nutrition, pregnancy and child-dose tools, cost optimizer, voice triage) are written by an AI model run by **our AI provider (Anthropic Claude or Google Gemini, whichever is active)**. To do this, the app sends your request to our server (hosted on Vercel), which passes it to that provider. Which provider is active can change over time; this policy covers both. During testing, our server may also return built-in sample replies without sending your request to any AI provider. We send it **only when you use an AI feature** — never in the background.

**What can be sent, depending on the tool you use:**

| What | When |
|---|---|
| Text you type or dictate: medicine names, symptoms, chat messages (the last 12 messages of the conversation), lab values, food names | Medicine search, interactions, Symptom Checker, Dr. Chat, Lab Report, Nutrition, Cost Optimizer, Voice Triage, etc. |
| **Photos** you take or choose: medicine strips/boxes, lab reports, prescriptions, food labels or meals. A photo can contain names, dates or other personal details printed on it. | Camera Scan, Medicine Scanner, Lab Report, Prescription, Nutrition Scanner |
| **Age and gender** | Symptom Checker, Dr. Chat |
| **Blood group, allergies, medical conditions, and the names of your active medicines** (from your profile and reminders) | Dr. Chat — sent together with your messages whenever you have filled in these profile fields |
| **Existing conditions** you select, duration and severity | Voice Triage |
| Age, weight, medicine and form | Child Dose Calculator |
| Pregnancy trimester and medicine | Pregnancy Safety |
| The language you chose | All AI features (so the answer comes back in that language) |

**Why:** only to generate the answer you asked for, and to make it safer and more relevant (for example, to warn about an allergy or an interaction with a medicine you already take). We do not use it for advertising or profiling.

**What is NOT sent:** text and images are sent without your name or email (but a photo can show names or other details printed on it). Also not sent: your name, email, phone number, location, contact list, or reminders other than active medicine names in Dr. Chat. Our own server code does not store your messages or photos.

**Your choice and consent:** AI features are optional. By accepting the first-launch notice and then using an AI feature, you agree that the data above is sent to our AI provider (Anthropic Claude or Google Gemini, whichever is active) for that request. If you do not agree, do not use the AI features — the rest of the app (reminders, tracking, family hub, emergency card) works without sending anything to an AI provider. You can also leave allergies, conditions and other profile fields empty so they are never included. You can withdraw consent at any time by no longer using AI features, and you can ask us to delete your account and data (Section 8).

**How our AI providers handle it:** Whichever provider is active processes the request under its own terms and privacy policy — Anthropic (anthropic.com/legal) or Google for the Gemini API (policies.google.com). Each provider may keep requests for a limited time for safety and abuse checks, and their rules on retention and on using data to improve their services can differ by provider and plan. We do not control these; please read their terms. Please do not include information in an AI request that you are not comfortable sending.

**Our server and abuse protection:** to stop misuse, our server checks your anonymous/account ID token and counts requests per user and per IP address using Upstash (a Redis service). These counters hold only an ID or IP address and a number, and expire within about a day. Our hosting provider (Vercel) may keep normal request logs, including IP address. Our server code does not write the content of your requests to its logs.

AI answers can be wrong. They are information, not medical advice (see our Medical Disclaimer).

---

## 4. What We Do NOT Collect
- We do **NOT** collect your precise location for tracking (a one-time coarse fix is used only when *you* tap "Share Live Location" in Emergency SOS, and is never stored)
- We do **NOT** use advertising SDKs, tracking pixels, or cross-app identifiers
- We do **NOT** build advertising or marketing profiles about you
- We do **NOT** send your health data, medicine names, or message content to analytics (the AI requests in Section 3 are separate from analytics)
- We do **NOT** sell your data to third parties — **ever**
- We do **NOT** share your health data with insurance companies, employers, or marketers
- Our own server code does **NOT** store your messages or photos

---

## 5. Third-Party Services We Use

| Service | Purpose | Data Shared |
|---|---|---|
| Firebase Authentication (Google) | User login | Email, name, Google profile |
| Anthropic (Claude API) — one of our two AI providers, used when active | AI-powered health responses | What you submit to an AI feature: text, photos, and (in some tools) age, gender, blood group, allergies, conditions, medicine names — see Section 3 |
| Google (Gemini API) — one of our two AI providers, used when active | AI-powered health responses | The same data as the Anthropic row above — see Section 3 |
| Vercel (our server host) | Runs the AI server that passes your request to the active AI provider | The same request while it is being processed; standard request logs (IP address) |
| Upstash (Redis) | Rate limiting to stop abuse | Account/anonymous ID or IP address with a request count, expires within about a day |
| Firebase Crashlytics | Crash & error diagnostics | Stack traces, device/OS, anonymous app-instance & user ID |
| Firebase Analytics | Anonymous feature-usage counters | Event names + category labels only — never health content |
| Firebase Performance Monitoring | App speed / reliability | App-start and network timings, device/OS |
| Your email provider (via *Send Feedback*) | Deliver feedback you choose to send | Your message + app version/device model, sent from your own mail app |

No advertising, marketing, or data-broker SDKs are used.

---

## 6. How We Use Your Data

| Data | Purpose |
|---|---|
| Email / Firebase UID | Account login, session management |
| Medication reminders | Show you your own reminders and adherence stats |
| Symptom/chat history | Display your past Dr. Chat conversations (saved on your phone) |
| Text, photos and profile details you submit to an AI feature | Generate the AI answer for that request (Section 3) |
| Anonymous/account ID and IP address | Verify the request and limit abuse |
| App preferences | Personalize your experience |

We use your data **only** to operate the app features you use. No profiling, no advertising.

---

## 7. Data Storage & Security

- **Health profile, reminders and history** → Stored locally on your Android device only
- **Auth data** → Stored securely on Firebase servers (Google Cloud, ISO 27001 certified)
- **AI requests** → Sent over encrypted HTTPS through our server to the active AI provider (Anthropic or Google Gemini) (Section 3). Our own server code does not store them; the provider may keep them under its own terms.
- Local data is protected by your device's security (screen lock, encryption)
- The app's data is excluded from Android cloud backup and device-to-device transfer, so it is not copied to Google Drive or to a new phone

---

## 8. Data Retention & Deletion

- You can delete your account and all data stored on your phone at any time: **Profile tab (scroll to the bottom) → Delete account & data**. This also works for guests.
- You can also ask for deletion on the web at **https://legal.mediscanai.app/delete-account.html** or by email (Section 13). An email request deletes your account held on our servers; data on your phone is removed from the phone itself (the in-app delete, Android **Clear storage**, or uninstalling the app).
- On account deletion, your Firebase auth record is permanently removed, your medicine-reminder notifications are cancelled, and the app's analytics ID on your phone is reset. Data already received by Google Firebase analytics/crash services is kept by Google for its own retention period and is not linked to your name or email.
- Data already sent to an AI provider for a request is held under that provider's terms; we cannot delete it from their systems, and we do not keep a copy. To ask questions, contact us (Section 13).

---

## 9. Children's Privacy

MediScanAI is **not intended for children under 13 years of age.** We do not knowingly collect personal data from children. If you believe a child has used this app and provided personal data, please contact us immediately at the email below.

---

## 10. Your Rights Under DPDP Act 2023

As per the Digital Personal Data Protection Act, 2023 (India), you have the right to:

- **Access** — Know what personal data we hold about you
- **Correction** — Request correction of inaccurate data
- **Erasure** — Request deletion of your personal data
- **Withdraw consent** — stop using AI features at any time; ask us to delete your account
- **Grievance Redressal** — Raise a complaint about data handling

To exercise any of these rights, contact us at: **support@mediscanai.app**

We will respond within **30 days** of receiving your request.

---

## 11. International Users

MediScanAI is developed and operated from India. AI requests are processed by our AI provider (Anthropic or Google) and our hosting providers, whose servers may be outside India (for example in the United States). If you use AI features, you understand your request may be processed outside your country.

---

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will:
- Update the "Last Updated" date at the top
- Notify you via an in-app notification on next launch

Continued use of the app after changes means you accept the updated policy.

---

## 13. Contact Us

For privacy concerns, data requests, or grievances:

**Email:** support@mediscanai.app  
**App Name:** MediScanAI  
**Developer:** MediScanAi-official  
**Country:** India

---

*Your health records stay on your phone. The only data that leaves it is what you choose to send to an AI feature — and we tell you exactly what that is.*
