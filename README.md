# 🖇️ Stationery Store Management System with Receipt Generation and Data Encryption

A Python-based application for managing stationery sales, generating PDF receipts, and securely storing transaction data. This system was developed during my role as a **Python Programmer at Cipherbyte Technologies**.

## 🔧 Technologies Used

* **Python**
* **SQLite**
* **ReportLab** – PDF receipt generation
* **Fernet (Cryptography library)** – Data encryption
* **datetime**, **os**

## ✨ Key Features

* 🛍️ Allows users to select stationery items and quantities
* 📋 Stores item and transaction data using SQLite
* 🔐 Encrypts sensitive information like transaction IDs using Fernet
* 🧾 Generates PDF receipts with itemized purchases using ReportLab
* 🗃️ Automatically names and stores receipts with timestamps

## 📁 Project Structure

```
Stationery-Store-Management-System/
│
├── main.py                  # Core application logic
├── database.db              # SQLite database with item and transaction tables
├── receipts/                # Folder for generated PDF receipts
├── utils/
│   ├── encryption.py        # Encryption/decryption logic using Fernet
│   └── receipt_generator.py # Receipt creation with ReportLab
└── README.md                # Project documentation
```

## ▶️ How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/atharvaballa/Stationery-Store-Management-System-with-Receipt-Generation-and-Data-Encryption.git
   cd Stationery-Store-Management-System-with-Receipt-Generation-and-Data-Encryption
   ```

2. **Install dependencies**

   ```bash
   pip install cryptography reportlab
   ```

3. **Run the application**

   ```bash
   python main.py
   ```

## 🔐 Data Security

* Uses **Fernet** encryption to secure transaction IDs and sensitive data.
* Ensures integrity by storing receipts with timestamped filenames.
* No sensitive info is stored in plain text.

## 📈 Possible Enhancements

* GUI using Tkinter or PyQt
* Role-based authentication (admin/staff)
* Export sales reports in Excel format
* Email receipts to customers

## 🧑‍💻 Author

**Atharva Balla**
*Developed at Cipherbyte Technologies as part of a professional internship project.*
[GitHub Profile](https://github.com/atharvaballa)
