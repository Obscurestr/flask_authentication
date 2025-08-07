# Flask Authentication App

This is a simple Flask web application that demonstrates user registration, login, authentication, and secure content access using **Flask-Login**, **SQLAlchemy**, and **Werkzeug**.

## 🚀 Features

- ✅ User registration with email, name, and password  
- 🔐 Password hashing using `pbkdf2:sha256`  
- 🔓 User login and logout  
- 🔒 Secure page accessible only to logged-in users  
- 💬 Flash messaging for user feedback  
- 📁 Downloadable file available for authenticated users  
- 🎨 Fully styled with Bootstrap  

---

## 🛠 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Obscurestr/flask_authentication.git
cd flask_authentication
```

### 2. Create and activate a virtual environment *(optional but recommended)*

**On macOS/Linux:**

```bash
python -m venv venv
source venv/bin/activate
```

**On Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install flask flask_sqlalchemy flask_login
```

Or if you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

---

## 🌐 Open in your browser

```
http://127.0.0.1:5000/
```

---

## 📂 Folder Structure

```
flask_authentication/
│
├── app.py
├── requirements.txt
├── templates/
│   └── ...
├── static/
│   └── ...
└── README.md
```

---
 
