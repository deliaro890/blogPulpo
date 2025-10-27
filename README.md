Django Blog App is a full-featured blogging platform built with Django, allowing users to create, edit, and publish posts with image uploads and authentication.
It’s designed to be lightweight, secure, and fully customizable — ideal as a starter project or content management demo.

🚀 Features

👤 User authentication (register, login, logout)

📝 Create, edit, and delete blog posts

🖼️ Upload and display featured images

🗂️ Categorization by author and date

🔍 Clean UI using Django Templates

🧩 Admin panel for managing users and posts

🌐 Responsive design

🛠️ Tech Stack
Layer	Technology
Backend	Django (Python)
Frontend	HTML, CSS, Bootstrap
Database	SQLite / MySQL
Authentication	Django Auth System
Deployment	Linux (Ubuntu/CentOS) + Gunicorn + Nginx
Version Control	Git & GitHub
📂 Project Structure
django-blog-app/
├── blog/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── templates/blog/
├── users/
│   ├── forms.py
│   ├── views.py
│   ├── urls.py
│   └── templates/users/
├── static/
├── media/
├── manage.py
└── requirements.txt

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/deliaro890/django-blog-app.git
cd django-blog-app

2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run migrations
python manage.py migrate

5️⃣ Create a superuser
python manage.py createsuperuser

6️⃣ Start the server
python manage.py runserver


Visit 👉 http://127.0.0.1:8000/

Admin panel 👉 http://127.0.0.1:8000/admin

🧾 Example Pages
URL	Description
/	Home page with all blog posts
/post/<id>/	Individual post view
/post/new/	Create new post
/post/<id>/edit/	Edit existing post
/login/	User login
/register/	Create new user
/logout/	Logout
🐳 Deployment (Optional)

Example setup:

VPS running Ubuntu

Gunicorn as WSGI server

Nginx as reverse proxy

Media and static files served from /var/www/html/media and /static

👩‍💻 Author

Delia Cristina Román García
Web Developer (Full Stack – Python | Node | Docker | Linux)
📍 Dublin, Ireland
📧 delir890@gmail.com

🔗 GitHub – deliaro890

🏷️ License

MIT License © 2025 — Delia Cristina Román García
