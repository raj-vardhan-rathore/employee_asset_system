# 🏢 AssetFlow Pro - Employee & Asset Management System

**AssetFlow Pro** is a responsive and interactive web application built using HTML, CSS, and JavaScript that helps manage employees and organizational assets. It provides dashboard analytics, employee and asset management, assignment tracking, reporting, and advanced utilities like QR/barcode simulation, audit logs, and auto-save support.

---

## 🌟 Features

- 📊 **Dashboard Overview** — Real-time stats on employees and assets
- 👥 **Employee Management** — Add, edit, delete, and search employees
- 💻 **Asset Management** — Manage organizational assets and their assignments
- 📋 **Asset Assignment** — Assign and track asset usage
- 📈 **Reports** — Generate employee, asset, and assignment reports
- 🔐 **Role-based Access Simulation**
- 🧠 **Data Persistence (Simulated LocalStorage)**
- 📱 **QR & Barcode (Mockup)**
- 📤 **Bulk Import (CSV/JSON - Simulated)**
- 🗂 **Audit Logs** — View activity history

---

## 📁 Project Structure

```
employee_asset_system.html      # Main application file (HTML, CSS, JS combined)
README.md                       # Project documentation
requirements.txt                # Required software (basic tools)
```

---

## ⚙️ Requirements

This project runs purely in the browser. No installation needed.

> 📌 Make sure to use a modern browser like **Google Chrome**, **Firefox**, or **Edge**.

---

## 🚀 How to Use

1. **Download or Clone** the repository:
   ```bash
   git clone https://github.com/yourusername/assetflow-pro.git
   cd assetflow-pro
   ```

2. **Open the app**:
   - Simply double-click `employee_asset_system.html` or
   - Run in browser:  
     ```bash
     start employee_asset_system.html  # Windows  
     open employee_asset_system.html   # macOS
     ```

3. **Start managing** your employees and assets effortlessly.

---

## 🔐 Simulated Admin Access

- User: `Admin`  
- Role: `admin`  
- Permissions: `['create', 'read', 'update', 'delete', 'assign', 'report']`

> This is a simulated role-based model. You can extend it with login capabilities.

---

## 📦 Export & Save Options

- JSON exports available for Employees and Assets
- Auto-save runs every 30 seconds (console log simulating localStorage)
- Data persistence is mockup, extendable via IndexedDB or backends

---

## 📌 Note

This project is a **front-end only** prototype designed for presentation/demo purposes. It does not include real authentication or a backend server.

---

## 📃 License

MIT License — feel free to use and modify!

---

## ✨ Made By

Raj Vardhan
