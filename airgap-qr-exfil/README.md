# 🧠 Payload Name  
**Airgap QR Exfiltration**

---

## 📝 Description

This payload silently exfiltrates sensitive data from a Windows machine **without any internet connection**.  
It collects:

- 📋 Clipboard contents  
- 👤 Username  
- 💻 Hostname  
- 🕓 Timestamp  

Then it Base64 encodes the data, URL-encodes it, and opens a QR code in Chrome.  
The attacker can simply scan the QR with a smartphone and decode the string manually using a base64 decoder.

---

## 🎯 Purpose

Designed for air-gapped or offline environments, this payload demonstrates that even isolated machines can leak critical data in seconds through a clever side-channel: **visual exfiltration via QR code**.

No admin privileges, no network access, and no file writes required.

---

## ✅ Benefits

- ❌ No outbound network connections  
- 🔐 Works in restricted environments  
- 🧼 Leaves no trace on disk  
- 🕶️ Extremely stealthy and fast  
- 🛠️ Great for Red Team / pentest / physical ops  

---

## 🔐 Notes

> Only for use in **authorized security assessments** or **educational purposes**.  
> Misuse of this tool may violate laws and ethical guidelines.

---

## 📁 File Structure
