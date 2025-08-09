# 📡 Intercept SMS Bot Using SS7 Attacks

**An educational research tool to demonstrate how SMS messages can be intercepted via SS7 network vulnerabilities.**  
> ⚠️ FOR EDUCATIONAL PURPOSES ONLY & ILLEGAL USE IS STRICTLY PROHIBITED.

---

## 🔍 What is SS7?

SS7 (Signaling System No. 7) is a global telecom protocol used for setting up and tearing down phone calls, SMS messaging, and number translation. Due to outdated trust models, the SS7 network is vulnerable to **location tracking**, **call interception**, and **SMS redirection**—even across different countries and carriers.

**Access to SS7 Attack Bot**: https://t.me/intercept_sms_bot

---

## 🤖 What is an SS7 SMS Interception Bot?

This project simulates a bot that exploits SS7 signaling flaws to **intercept one-time passwords (OTP)** and **SMS-based 2FA messages** by manipulating the global mobile switching infrastructure.

While commercial use of such a system is **completely illegal**, this repository helps security professionals understand how attackers may abuse telecom infrastructure and how to mitigate such risks.

---

## ⚙️ How the SMS Interception Bot Works

1. **Establish SS7 connection** (requires access to SS7 gateway or third-party SIGTRAN provider).
2. **Send MAP-SEND-ROUTING-INFO-FOR-SM** request to retrieve victim's MSC.
3. **Send MAP-FORWARD-SHORT-MESSAGE** to hijack SMS delivery.
4. Extract OTP or verification code from intercepted message body.

---

## 🚨 Legal Warning & Ethical Usage

This tool is for **educational cybersecurity research** only.

Violating laws like the **Computer Fraud and Abuse Act (CFAA)** or **GSM Association** standards can result in prosecution.

---

## ✨ Features of SMS Interceptor Bot

- Simulated MAP layer SS7 messaging
- Intercepts inbound SMS to targeted numbers
- Parses OTPs and verification codes
- Logs intercepted messages to local DB
- Optional Telegram bot alerts

---
