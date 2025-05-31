# 🚀 Redis Integration in MERN Backend

This document explains how Redis is used in the backend of this MERN stack application. Redis is a powerful in-memory data store used for:

- 🔁 Caching
- 🔐 Session management & OTP storage
- 📉 Reducing database load
- 🚦 Rate limiting
- 📬 Queues & Pub/Sub (optional)

---

## 📦 Why Redis?

- ⚡ Super fast (in-memory)
- 📥 Reduces DB queries via caching
- 🕐 Perfect for temporary or expiring data (e.g., OTPs, tokens)
- 🧰 Versatile utility for advanced backend features

---

## ⚙️ Installation

### 1. Install Redis on Ubuntu

```bash
sudo apt update
sudo apt install redis
sudo systemctl enable redis
sudo systemctl start redis
