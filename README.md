# 🏛️ Yojana Setu — योजना सेतु

> **India's Government Schemes Awareness Platform**  
> A fully standalone, single-file website. No server. No database. No installation required.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge)](https://YOUR-USERNAME.github.io/yojana-setu)
[![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=for-the-badge&logo=html5)](index.html)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 🌟 Features

| Feature | Description |
|---|---|
| 📋 **32 Real Schemes** | PM-KISAN, Ayushman Bharat, PMAY, Mudra, NSP, PMKVY, and 26 more |
| 🔍 **Smart Filters** | Filter by Category, Government Type, Status, State, and Keyword |
| 🔐 **Auth System** | Register, Login, Logout, Forgot Password — all saved in browser |
| 💾 **Save Schemes** | Bookmark schemes to personal dashboard |
| 📊 **Admin Panel** | View all users, activity logs, login/logout history |
| 📥 **Excel Export** | Download full user data report with 6 sheets |
| 📱 **Responsive** | Works on mobile, tablet, and desktop |
| ⚡ **Zero Setup** | Just open `index.html` — works offline too |

---

## 🚀 Quick Start

### Option 1 — Open Directly
```
1. Download or clone this repo
2. Double-click index.html
3. Opens in any browser instantly
```

### Option 2 — GitHub Pages (Recommended)
```
1. Fork this repository
2. Go to Settings → Pages
3. Set Source: Deploy from branch → main → / (root)
4. Your site is live at: https://YOUR-USERNAME.github.io/yojana-setu
```

### Option 3 — Clone & Run
```bash
git clone https://github.com/YOUR-USERNAME/yojana-setu.git
cd yojana-setu
# Just open index.html in browser — done!
```

---

## 🔐 Admin Panel

> Track every registration, login, logout, and password reset in real time.

**How to open:**  
Scroll to the very bottom of the page → click the tiny **⚙** symbol in the footer

**Password:** `Admin@123`

### Admin Features
| Tab | What you see |
|---|---|
| 👥 Members | All registered users with name, email, password, mobile, login count |
| 📋 Activity Log | Every action — register, login, logout, failed attempts |
| 🔑 Logins | All successful and failed login history |
| 🚪 Logouts | All logout and password reset events |

### Excel Download
Click **📥 Download Excel** inside the admin panel to get a `.xlsx` file with:
- Sheet 1: All Members
- Sheet 2: Full Activity Log  
- Sheet 3: Registrations
- Sheet 4: Login History
- Sheet 5: Logouts & Password Resets
- Sheet 6: Summary Statistics

---

## 📋 Schemes Included

### Central Government (23)
PM-KISAN · Ayushman Bharat (PMJAY) · PM Awas Yojana Urban · PM Mudra Yojana · National Scholarship Portal · PMKVY 4.0 · Beti Bachao Beti Padhao · Atal Pension Yojana · PM Jan Dhan Yojana · Startup India · PM Fasal Bima Yojana · MGNREGS · PM Surya Ghar · PMJJBY · PMSBY · Jal Jeevan Mission · PMEGP · Stand Up India · PM Matru Vandana Yojana · PM Internship Scheme · NDHM/ABDM · PM Shram Yogi Maan-Dhan · Samagra Shiksha · Digital India · PM Awas Yojana Gramin · Viksit Bharat 2047

### State Government (6)
Rythu Bandhu (Telangana) · KALIA (Odisha) · Ladli Behna Yojana (MP) · Mahila Samman Yojana (Delhi) · Mukhyamantri Chiranjeevi Bima (Rajasthan) · Mukhyamantri Mahila Uttkarsh Yojana (Gujarat)

---

## 🗂️ Project Structure

```
yojana-setu/
├── index.html          ← Entire website (single file)
├── README.md           ← This file
├── LICENSE             ← MIT License
└── .github/
    └── workflows/
        └── deploy.yml  ← Auto GitHub Pages deployment
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **Vanilla HTML/CSS/JS** | No frameworks, no dependencies |
| **SheetJS (CDN)** | Excel file generation |
| **localStorage** | User data, activity logs, saved schemes |
| **CSS Variables** | Theming — Saffron, Navy, Green (Indian flag colours) |

---

## ⚠️ Disclaimer

This is an **awareness platform only** and is **not an official government website**.  
All scheme information is sourced from official `.gov.in` websites.  
Always verify information directly from official government sources before applying.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<div align="center">
  Made with ❤️ for Digital India 🇮🇳
</div>
