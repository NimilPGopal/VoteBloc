<div align="center">

# 🗳️ VoteBloc
### *Trust in Every Ballot*

**A secure, transparent, and blockchain-powered online voting system**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Django](https://img.shields.io/badge/Django-4.x-092E20?style=for-the-badge&logo=django&logoColor=white)](https://djangoproject.com)
[![Blockchain](https://img.shields.io/badge/Blockchain-Enabled-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Overview

**VoteBloc** is a full-stack web application that revolutionizes the way elections are conducted by leveraging **blockchain technology** to ensure every vote is **secure, immutable, and transparent**. Built with Django, VoteBloc empowers administrators, sub-admins, election coordinators, and voters in a trustworthy and inclusive electoral process.

> 🏛️ *"Voting Made Safe and Simple."*

---

## 🖼️ Screenshots

| Home (Admin) | Login | Sub-Admin Dashboard |
|:---:|:---:|:---:|
| ![Home](SS/Screenshot%20(71).png) | ![Login](SS/Screenshot%20(70).png) | ![SubAdmin](SS/Screenshot%20(74).png) |

---

## ✨ Features

- 🔗 **Blockchain-Backed Voting** — Every vote is recorded on an immutable blockchain ledger
- 🛡️ **Role-Based Access Control** — Admin, Sub-Admin, Election Coordinator, and Voter roles
- 🗳️ **Election Management** — Create, manage, and monitor elections end-to-end
- 🏛️ **Party Management** — Register and approve political parties
- 📊 **Real-Time Results** — Transparent, tamper-proof vote counting
- 📣 **Complaint System** — Built-in complaint and grievance management
- 👤 **Voter Profiles** — Secure voter registration and identity management
- 📱 **Responsive UI** — Clean and modern interface accessible on all devices

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Python, Django |
| **Blockchain** | Custom blockchain implementation |
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap |
| **Database** | SQLite (dev) / PostgreSQL (prod) |
| **Auth** | Django Auth + Session Management |
| **Hosting** | Localhost / Deployable to any cloud |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- pip
- virtualenv (recommended)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/NimilPGopal/VoteBloc.git
cd VoteBloc

# 2. Extract the project zip
# Unzip votebloc(Final).zip into this directory

# 3. Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate      # Windows
# source venv/bin/activate  # macOS/Linux

# 4. Install dependencies
pip install -r requirements.txt

# 5. Apply database migrations
python manage.py migrate

# 6. Create a superuser (Admin)
python manage.py createsuperuser

# 7. Run the development server
python manage.py runserver
```

Then open your browser and visit: **http://127.0.0.1:8000/**

---

## 👥 Roles & Access

| Role | Description |
|---|---|
| **Admin** | Full system control — manage elections, parties, sub-admins |
| **Sub-Admin** | Manage regional elections and coordinators |
| **Election Coordinator** | Oversee specific elections, approve candidates |
| **Voter** | Register, authenticate, and cast votes securely |

---

## 📁 Project Structure

```
VoteBloc/
├── votebloc(Final).zip     # Main project source code
├── Blocvote(Final).zip     # Additional module/variant
├── SS/                     # Application screenshots
│   ├── Screenshot (69-74).png
│   └── ...
├── VOTEBLOC Presentation.pdf
├── VoteBloc LinkedIn_Doc.pdf
├── .gitignore
└── README.md
```

---

## 📄 Documentation

- 📊 [Project Presentation](VOTEBLOC%20Presentation.pdf) — Full project overview and architecture
- 📝 [LinkedIn Document](VoteBloc%20LinkedIn_Doc.pdf) — Project summary and highlights

---

## 👨‍💻 Team — Executed By

| Name | Role |
|---|---|
| **Nimil P Gopal** | Lead Developer |
| **Sidharth K Harihar** | Developer |
| **Manav Shaji** | Developer |
| **Hariprasad AP** | Developer |

> 📍 Developed at **IHRD, Calicut, Kerala, India**

---

## 🌟 Mission & Vision

**Our Mission:** Empowering democracy through secure and transparent blockchain-based voting solutions.

**Our Vision:** Building a future with secure, transparent, and inclusive voting through innovative blockchain solutions.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

© 2024 VoteBloc. All rights reserved. Design by **BlocVote**

⭐ *If you found this project helpful, please give it a star!* ⭐

</div>
