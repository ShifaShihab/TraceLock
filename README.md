# TraceLock 🔐

### Blockchain-Based Evidence Integrity System

TraceLock is a **Blockchain Concept based Digital Evidence Integrity System** designed to securely manage and verify digital evidence using **SHA-256 hash chaining**.
The project ensures that uploaded evidence remains tamper-proof while maintaining transparent audit trails and authenticity verification.

Built using **Python**, **Tkinter**, **JSON**, and **ReportLab**, TraceLock provides a lightweight desktop solution for secure forensic evidence management.

---

# 📌 Features

* 🔑 **Officer & Admin Authentication**
* 📂 **Create and Manage Cases**
* 📤 **Secure Evidence Upload**
* 🔗 **SHA-256 Hash Chaining**
* 🚨 **Tamper Detection System**
* 📝 **Audit Log Monitoring**
* 📄 **PDF Authenticity Certificate Generation**
* 🗃️ **JSON-based Evidence Storage**
* 🖥️ **Simple GUI using Tkinter**

---

# 🛠️ Tech Stack

| Technology | Purpose                    |
| ---------- | -------------------------- |
| Python     | Core Programming           |
| Tkinter    | GUI Interface              |
| SHA-256    | Hash Integrity             |
| JSON       | Data Storage               |
| ReportLab  | PDF Certificate Generation |

---

# 📂 Project Structure

```bash
TraceLock/
│
├── main.py
├── data/
├── reports/
├── evidence/
├── screenshots/
│
├── adminlogin_img.png
├── admindash_img.png
├── offlogin_img.png
├── offdash_img.png
├── newcase_img.png
├── evidence_img.png
├── tampered_img.png
├── blocks_img.png
├── auditlog_img.png
├── auditlog_json.png
├── chainjson_img.png
├── reportpdf_img.png
│
└── README.md
```

---

# ⚙️ How It Works

1. Officer/Admin logs into the system.
2. A new case is created.
3. Evidence files are uploaded.
4. Each evidence entry generates a SHA-256 hash.
5. Hashes are chained together like blockchain blocks.
6. Any modification triggers tamper detection.
7. Audit logs track every activity.
8. Authenticity certificates can be exported as PDF reports.


---

# 📸 Screenshots

## 🔐 Officer Login

```md
![Officer Login](screenshots/offlogin_img.png)
```

## 🖥️ Officer Dashboard

```md
![Officer Dashboard](screenshots/offdash_img.png)
```

## 🔑 Admin Login

```md
![Admin Login](screenshots/adminlogin_img.png)
```

## 📊 Admin Dashboard

```md
![Admin Dashboard](screenshots/admindash_img.png)
```

## 📁 Create New Case

```md
![New Case](screenshots/newcase_img.png)
```

## 📤 Evidence Upload

```md
![Evidence Upload](screenshots/evidence_img.png)
```

## 🔗 Blockchain Blocks

```md
![Blockchain Blocks](screenshots/blocks_img.png)
```

## 🧾 Chain JSON Data

```md
![Chain JSON](screenshots/chainjson_img.png)
```

## 📝 Audit Logs

```md
![Audit Logs](screenshots/auditlog_img.png)
```

## 📄 Audit Log JSON

```md
![Audit Log JSON](screenshots/auditlog_json.png)
```

## 🚨 Tamper Detection

```md
![Tamper Detection](screenshots/tampered_img.png)
```

## 📑 PDF Authenticity Certificate

```md
![PDF Report](screenshots/reportpdf_img.png)
```

---

# 🔒 Security Concept

TraceLock follows a blockchain-inspired architecture where:

* Every evidence item contains:

  * Previous Hash
  * Current Hash
  * Timestamp
  * Evidence Metadata

* Any change in stored evidence:

  * Changes the hash
  * Breaks the chain
  * Triggers tamper alerts

This ensures integrity and authenticity of digital evidence.

---

# 📜 Future Improvements

* Cloud Database Integration
* Multi-user Access Control
* Real Blockchain Integration
* Digital Signature Verification
* AES Encrypted Evidence Storage
* Web-based Dashboard

---

# 👨‍💻 Project Team

TraceLock was developed as a collaborative academic project by:

- **Shifa Shihab**
- **Niranjana P**
- **Safa Fathima**
- **Krishna P V**

# ⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
🛠️ Contribute improvements

---

# 📄 License

This project is developed for educational and academic purposes.


