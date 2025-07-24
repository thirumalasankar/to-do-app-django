<img width="271" height="627" alt="image" src="https://github.com/user-attachments/assets/6503cab1-e5fb-4ccf-8160-7d0997d09d3f" /># 📝 Django To-Do App

A simple yet functional To-Do list application built using Django. This project demonstrates core Django concepts including user authentication, CRUD operations, and a clean UI for task management.

---

## 📌 Features

- ✅ User Registration & Login
- ✅ Add new tasks
- ✅ Update existing tasks
- ✅ Delete tasks
- ✅ Logout
- ✅ Responsive UI with Bootstrap
- ✅ Secure user session management
- ✅ Deployed on Render (or Heroku)

---

## 📷 Screenshots

> You can add your screenshots here later (optional


---

## 🚀 Live Demo

> If deployed, paste your Render/Heroku app link here  
`https://your-app-name.onrender.com/`

---

## 🧰 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (can be replaced with PostgreSQL)
- **Deployment:** Render (or Heroku)

---

## 📂 Project Structure

<img width="271" height="627" alt="image" src="https://github.com/user-attachments/assets/3d5030a7-4c1c-4bfe-9ccb-4fe6398c648d" />


---

## ⚙️ Getting Started (Local Setup)

1. Clone the Repository

git clone https://github.com/thirumalasankar/to-do-app-django.git
cd to-do-app-django

2. Create and Activate Virtual Environment

python -m venv venv
venv\Scripts\activate   # On Windows

# OR
source venv/bin/activate   # On macOS/Linux

3. Install Dependencies
pip install -r requirements.txt

4. Apply Migrations
python manage.py migrate

5. Run the Development Server
python manage.py runserver

Now visit http://127.0.0.1:8000 in your browser.

Create a Superuser (Admin Panel)
python manage.py createsuperuser
Visit: http://127.0.0.1:8000/admin to log in as admin.

🌐 Deployment (on Render)
1. Create a new repo on GitHub and push your code
2. Go to Render.com
Create a new Web Service

Connect your GitHub repo

Build Command: pip install -r requirements.txt

Start Command: gunicorn todopr.wsgi:application

Add Environment Variables:

SECRET_KEY

DEBUG=False

Add a file named render.yaml (optional for auto-deploys)

3. Done! Render will host your app and give you a live URL

