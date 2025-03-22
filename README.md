# 🚀 User Authorization System with Django

A *user authentication system* built with Django that allows users to *register, log in, and securely store their details* in a database. Passwords are hashed for security, ensuring a safe and robust authentication mechanism.

---

## ✅ *Features*
- 🔐 *User Registration (Signup)*  
- 🔑 *Secure Login & Logout*  
- 🔒 *Password Hashing for Security*  
- 📄 *User Details Stored in Database*  
- ⚙ *Django Authentication System*
- 🔏 *Admin Panel for User Management*
- 🔥 *Session Management & CSRF Protection*
- 🌐 *Responsive UI with Bootstrap*

---

## 🛠 *Technologies Used*
- *Backend:* Django (Python)  
- *Database:* SQLite 
- *Frontend:* HTML, CSS, Bootstrap 
- *Authentication:* Django’s built-in authentication system  
- *Version Control:* Git & GitHub  
- *Security:* CSRF protection, password hashing, and session management  

---

## 📌 *Setup & Installation*

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/HarshKhetan20/User_Authorization.git

cd User_Authorization

```
 ---

2️⃣ Create a Virtual Environment


On macOS/Linux
```
python -m venv venv

source venv/bin/activate
```
On Windows
```
python -m venv venv

venv\Scripts\activate
```
3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

---


4️⃣ Apply Migrations
```sh
python manage.py makemigrations
python manage.py migrate
```

---


5️⃣ Create a Superuser (Optional, for Admin Access)
```sh
python manage.py createsuperuser
```

---


6️⃣ Run the Development Server
```
python manage.py runserver
```
Visit http://127.0.0.1:8000/ in your browser to test the application.

---

# 🛡️ Security  
- Uses Django's built-in authentication for **secure password hashing**.  
- Ensures user passwords are never stored in plain text.  
- Follows Django best practices for user authentication and session management.  

---

# 📜 License  
- This project is licensed under the **MIT License** – feel free to modify and use it.  

---




