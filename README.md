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
├── __pycache__/
├── build/
│   └── tracelock/
│
├── data/
│   ├── evidence/
│   ├── admins.json
│   ├── audit.json
│   ├── cases.json
│   ├── chain.json
│   ├── inadmissible.json
│   └── officers.json
│  
│
├── dist/
│   ├── data/
│   └── TraceLock.exe
│
├── audit.py
├── auth.py
├── blockchain.py
├── dashboard.py
├── main.py
│
├── BUILD_README.md
├── build.bat
├── tracelock.ico
├── tracelock.spec
├── version_info.txt
|
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
![Officer Login](<img width="1916" height="952" alt="offlogin_img" src="https://github.com/user-attachments/assets/740313ba-b252-42f1-83a2-ef53b4b22e4e" />)
```

## 🖥️ Officer Dashboard

```md
![Officer Dashboard](<img width="1912" height="989" alt="offdash_img" src="https://github.com/user-attachments/assets/ad58a23a-dab5-4033-b7ca-9b2faf2635cc" />)
```

## 🔑 Admin Login

```md
![Admin Login](<img width="1918" height="960" alt="adminlogin_img" src="https://github.com/user-attachments/assets/0c5b75b4-1ddf-4ccb-9f00-4b87cfe8ea0b" />)
```

## 📊 Admin Dashboard

```md
![Admin Dashboard](<img width="1904" height="954" alt="admindash_img" src="https://github.com/user-attachments/assets/4a0651b4-c4dc-4b71-a2a9-59612296df73" />)
```

## 📁 Create New Case

```md
![New Case](<img width="1911" height="978" alt="newcase_img" src="https://github.com/user-attachments/assets/d97ccaaa-5619-42dd-bc90-64b0616ceeca" />)
```

## 📤 Evidence Upload

```md
![Evidence Upload](<img width="1900" height="968" alt="evidence_img" src="https://github.com/user-attachments/assets/43e2ca09-2139-41f7-bbf1-0f9e9a665043" />)
```

## 🔗 Blockchain Blocks

```md
![Blockchain Blocks](<img width="1919" height="985" alt="blocks_img" src="https://github.com/user-attachments/assets/c14c565d-9a50-436e-ab28-3db5c5c887a8" />)
```

## 🧾 Chain JSON Data

```md
![Chain JSON](<img width="1130" height="632" alt="chain json_img" src="https://github.com/user-attachments/assets/04cd9529-9959-47d1-9c3b-2c6e83a6fb92" />)
```

## 📝 Audit Logs

```md
![Audit Logs](<img width="1898" height="978" alt="auditlog_img" src="https://github.com/user-attachments/assets/a2c829a3-fe15-46be-81dc-ac6bcdf0e908" />)
```

## 📄 Audit Log JSON

```md
![Audit Log JSON](<img width="1127" height="651" alt="auditlog_json" src="https://github.com/user-attachments/assets/57aa2c5f-7436-4f23-93d0-7f4573af6ee8" />)
```

## 🚨 Tamper Detection

```md
![Tamper Detection](<img width="1914" height="979" alt="tampered_img" src="https://github.com/user-attachments/assets/8cc65dd1-86d5-407d-b68c-95db241ae99b" />)
```

## 📑 PDF Authenticity Certificate

```md
![PDF Report](<img width="1014" height="843" alt="reportpdf_img" src="https://github.com/user-attachments/assets/63196318-7cdc-43fc-8577-7506de9256b7" />)
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


