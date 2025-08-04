This is a simple Flask web application that demonstrates user registration, login, authentication, and secure content access using Flask-Login, SQLAlchemy, and Werkzeug.

Features:
1.User registration with email, name, and password

2.Password hashing with pbkdf2:sha256

3.User login and logout

4.Secure page accessible only to logged-in users

5.Flash messaging for feedback

6.Downloadable file for authenticated users

7.Fully styled with Bootstrap

Installation
1.Clone the repo:
git clone https://github.com/Obscurestr/flask_authentication.git
cd flask_authentication

2.Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate (on Windows: venv\Scripts\activate)

3.Install dependencies:
pip install flask flask_sqlalchemy flask_login

4.Run the app:
python app.py

5.Open your browser:
http://127.0.0.1:5000/
