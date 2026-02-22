# 🔐 Secure QR Data Transfer

## 📌 Project Overview

The **SecureQr-DataTransfer** project provides a secure way to transfer text data using QR codes.

It uses encryption techniques to secure the message before converting it into a QR code. The QR code can then be scanned and decrypted on the receiving side to retrieve the original message securely.

This project demonstrates how cryptography and QR code technology can be combined to exchange data in a privacy-preserving manner.

---

## 🎯 Objectives

- Encrypt sensitive messages
- Generate QR codes for secure data transmission
- Decrypt data scanned from QR codes
- Learn practical applications of encryption & QR technology
- Create a simple secure communication prototype

---

## 🚀 Features

- 🔑 **Encryption of text messages**
- 📷 **QR Code generation**
- 🔓 **QR Code scanning & decryption**
- 🧠 Command-line execution
- 🛡️ Simple and secure workflow

---

## 🛠️ Technologies Used

- Python
- QRCode library (`qrcode`)
- OpenCV (`cv2`)
- Cryptography (`cryptography` module)
- NumPy
- Pyzbar (QR decoding)

---

## 📂 Project Structure

```bash
SecureQr-DataTransfer/
│
├── SecureQr-DataTransfer.ipynb      # Main project notebook
├── requirements.txt                 # Python dependencies
└── README.md                       # Project documentation
```

---

## ⚙️ How It Works

1. Enter a message you want to send securely
2. Message gets encrypted
3. Encrypted text is converted into a QR code
4. Receiver scans the QR code
5. Encrypted data is decrypted to get original message

This ensures that only authorized users can read the transferred data.

---

## ▶️ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Yaswanth000gsyr/SecureQr-DataTransfer.git
```

### 2️⃣ Navigate to the folder

```bash
cd SecureQr-DataTransfer
```

### 3️⃣ Install required dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the notebook

Open and run:

```
SecureQr-DataTransfer.ipynb
```

---

## 🧠 Algorithm Used

This project uses:

🎯 **Symmetric Encryption (Fernet)**  
- Provides encryption and decryption using the same secret key  
- Strong enough for secure message exchange  
- Easy to use with Python’s `cryptography` library  

QR code technology is used to convert encrypted data into a scannable form.

---

## 💡 Applications

- Secure message sharing
- Contactless secure information transfer
- Verification systems using encrypted QR codes
- Privacy-preserving data exchange
- Educational security projects

---

## 🔮 Future Improvements

- 🔐 Support asymmetric encryption (RSA)
- 📱 Build a mobile app interface
- 🌐 Add Web application frontend
- 📦 Create executable file
- 📹 Add live camera scanning UI

---

## 👤 Author

**Shanmukha Yaswanth Reddy**  
Computer Science Engineer  
Interested in Cryptography & Secure Systems

---

⭐ If you found this project useful, consider giving it a star!
