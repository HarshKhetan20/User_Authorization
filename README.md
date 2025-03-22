User Authorization System with Django

A user authentication system built with Django that allows users to register, log in, and store their details securely in a database. Passwords are hashed for security, ensuring a safe and robust authentication mechanism.

🚀 Features
✅ User Registration (Signup)
✅ Secure Login & Logout
✅ Password Hashing for Security
✅ User Details Stored in Database
✅ Django Authentication System

🛠️ Technologies Used
Backend: Django (Python)

Database: SQLite

Frontend: HTML, CSS, Bootstrap

📌 Setup & Installation
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/HarshKhetan20/User_Authorization.git
cd User_Authorization
2️⃣ Create a Virtual Environment
sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Apply Migrations
sh
Copy
Edit
python manage.py makemigrations
python manage.py migrate
5️⃣ Create a Superuser (Optional, for Admin Access)
sh
Copy
Edit
python manage.py createsuperuser
6️⃣ Run the Development Server
sh
Copy
Edit
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to test the application.

🛡️ Security
Uses Django's built-in authentication for secure password hashing.

Ensures user passwords are never stored in plain text.

Follows Django best practices for user authentication and session management.

📷 Screenshots
(Add screenshots here if available)

📜 License
This project is licensed under the MIT License – feel free to modify and use it.
