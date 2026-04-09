# 🔍 Gobuster - Directory Enumeration Notes

## 📌 Overview
Gobuster is a directory and file enumeration tool used to discover hidden endpoints on web servers.

---

## 🎯 Purpose
- Discover hidden directories  
- Identify exposed files  
- Expand attack surface  

---

## ⚙️ Command Example
```bash
gobuster dir -u http://example.com -w wordlist.txt
```
---
## 🧰 Flags
-u → target URL

-w → wordlist

-t → threads

-x → file extensions

---

## 📊 Sample Output

## 🔎 Output Meaning

200 → Accessible resource

301/302 → Redirect

403 → Forbidden (exists but restricted)

404 → Not Found

---

## 🧠 Key Takeaways

Learned directory enumeration

Interpreted HTTP status codes

---

## 🌍 Real-World Application

Useful for penetration testing to find hidden:

Admin pages (/admin)

Backup files (/backup)

Login portals (/login)


