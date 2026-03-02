# ⚡ GitHub Action Repository

This repository is used to trigger GitHub webhook events such as **Push**, **Pull Request**, and **Merge**.

---

## 🎯 Purpose

This repo acts as a **source of events** for the webhook system.

Whenever actions are performed here, GitHub sends webhook payloads to the backend service.

---

## 🔄 Triggered Events

The following events are used:

- ✅ Push  
- ✅ Pull Request  
- ✅ Merge (PR closed & merged)

---

## ⚙️ How It Works

1. Developer performs actions (push, PR, merge)
2. GitHub sends webhook events to backend endpoint
3. Backend processes and stores data in MongoDB
4. Frontend displays activity logs

---

## 🔗 Connected System

- 🔹 Webhook Endpoint: Flask Backend (webhook-repo)
- 🔹 Database: MongoDB
- 🔹 UI: React Dashboard

---

## 👨‍💻 Author

**Yash Janbandhu**