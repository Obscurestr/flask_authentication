This is a simple Flask web application that demonstrates user registration, login, authentication, and secure content access using Flask-Login, SQLAlchemy, and Werkzeug.

Features
User registration with email, name, and password

Password hashing with pbkdf2:sha256

User login and logout

Secure page accessible only to logged-in users

Flash messaging for feedback

Downloadable file for authenticated users

Fully styled with Bootstrap
Installation
Clone the repo:
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate (on Windows: venv\Scripts\activate)

Install dependencies:
pip install flask flask_sqlalchemy flask_login

Run the app:
python app.py

Open your browser:
http://127.0.0.1:5000/
