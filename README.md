# 🔐 Secure Data Encryption Web App

Welcome to the **Secure Data Encryption Web App**, a simple and powerful application built using **Python**, **Streamlit**, and **Fernet encryption** from the **cryptography** module. This tool allows you to securely encrypt and decrypt your sensitive data with a user-defined passkey.

---


## 🛠 Features

- 🔒 Passkey-Protected Encryption
- 🔑 Secure Decryption with Matching Passkey
- 💾 In-Memory Secure Storage (no files saved)
- 🚫 Access Control after Multiple Failed Attempts
- 🧪 Easy-to-Use Interface with Streamlit

---

## 📦 Requirements

Install dependencies with:
```bash
pip install -r requirements.txt
```

Make sure the following are included in your `requirements.txt`:
```
streamlit
cryptography
```

---


## 🧠 How It Works

- Users enter text and a passkey.
- The app encrypts the data using `Fernet` with the given key.
- Encrypted data is displayed and can be decrypted using the correct passkey.
- After 3 incorrect attempts, user must reauthorize.

---
## 🌐 Live Demo

Try the app here 👉 [Secure Data Encryption App](https://secure-data-encryption-rimshasultan.streamlit.app/)

---
**Happy Coding**👩🏻‍💻..

