# 🩺 Predico – General Disease Prediction System

> **An End-to-End Web Platform for Disease Prediction**  
> 🔮 Powered by **Django** & **Machine Learning**

![Python](https://img.shields.io/badge/Python-3.11-blue.svg?logo=python)
![Django](https://img.shields.io/badge/Django-4.x-success?logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-✔️-blue?logo=postgresql)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

### 🎯 Overview

**Predico** is an intelligent health assistant that predicts **general diseases based on patient symptoms** and allows **online doctor consultations** — all through an easy-to-use web interface.

🧠 Built with **Machine Learning**,  
🌐 Powered by **Django**,  
📊 Data-driven using **PostgreSQL**.

---

### 🚀 Features

- 🧬 Predicts diseases from **132 types of symptoms**
- 🧑‍⚕️ Suggests doctors based on predictions
- 📩 Supports **secure login**, **role-based access** (Patient, Doctor, Admin)
- 💬 Allows online consultations and feedback tracking
- 🔍 Integrated **ML model** trained on real-world medical data

---

### 🔧 Tech Stack

| Layer         | Tech Used                        |
|--------------|----------------------------------|
| Frontend      | HTML, CSS, JavaScript, Bootstrap |
| Backend       | Django (Python)                  |
| ML Framework  | scikit-learn                     |
| DB            | PostgreSQL                       |
| Tools         | PgAdmin, Orange ML               |

---

### 📦 How to Run Locally

> ✅ Make sure PostgreSQL & PgAdmin are installed before proceeding.

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/predico.git
cd predico

# 2. Create virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up PostgreSQL:
# Create a database manually named `predico` using PgAdmin or CLI

# 5. Apply migrations
python manage.py makemigrations
python manage.py migrate

# 6. Start the server
python manage.py runserver

# 7. Visit the app in your browser
http://127.0.0.1:8000/
