# 🎓 Certificate Registry System

A simple Python-based **Certificate Registry** that allows you to:

- ✅ Issue Certificates  
- 🔍 Verify Certificates  
- 🚫 Revoke Certificates  

This project uses **SHA-256 hashing** to ensure certificate authenticity and provides a simple **interactive terminal menu** for managing certificates.

---

## 📂 Project Structure

```
certificate_registry.py   # Main program
README.md                 # Documentation
```

---

## ⚙️ Features

1. **Issue Certificate**
   - Assigns a unique ID.
   - Stores details like student name, course, issuer, issue date, and file hash.
   - Prevents duplicate issuance for the same file.

2. **Verify Certificate**
   - Verifies a certificate using either the file path or its SHA-256 hash.
   - Returns certificate details if valid.

3. **Revoke Certificate**
   - Revokes a certificate by marking it as invalid.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/certificate-registry.git
   cd certificate-registry
   ```

2. Run the program:
   ```bash
   python certificate_registry.py
   ```

3. Use the **menu options**:
   ```
   === Certificate Registry Menu ===
   1. Issue Certificate
   2. Verify Certificate
   3. Revoke Certificate
   4. Exit
   ```

---

