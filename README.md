# 📝 Django Blogging Platform

A robust and feature-rich blogging application built using Django. This platform enables users to create, manage, and explore blog content seamlessly, while administrators can efficiently manage users and posts through a secure dashboard.

---

## 🚀 Features

### 📚 Content Management

* Full CRUD (Create, Read, Update, Delete) functionality for blog posts and categories.
* Secure and intuitive administrative dashboard.

### 👤 User Administration

* Superuser dashboard to manage users.
* Add, edit, delete accounts, and assign permissions.

### 🌐 Dynamic Frontend

* Responsive homepage displaying featured and recent posts.
* Category-based filtering for easy navigation.
* Full-text search to find articles by keywords.
* Detailed post view with an authenticated commenting system.

### 🔐 Authentication & Authorization

* User registration, login, and logout functionality.
* Permission-based access control for dashboard operations.

### 🔗 Automatic Slug Generation

* SEO-friendly and unique slugs for each blog post.

### 🖼️ Media Handling

<img width="1365" height="718" alt="Screenshot 2026-04-14 155341" src="https://github.com/user-attachments/assets/aa5a0762-9a7c-4469-9b8a-86cc35e3a436" />
<img width="1365" height="720" alt="Screenshot 2026-04-14 155357" src="https://github.com/user-attachments/assets/92957322-3d2d-45cb-bbd0-518faba517d2" />
<img width="1362" height="719" alt="Screenshot 2026-04-14 155415" src="https://github.com/user-attachments/assets/525599d4-bc48-4814-ad8a-5d73293e7a18" />
<img width="1365" height="720" alt="Screenshot 2026-04-14 155446" src="https://github.com/user-attachments/assets/63d3b054-a9b5-4c1f-be65-e090c9da7ed7" />



---

## 🛠️ Tech Stack

| Layer         | Technology                                     |
| ------------- | ---------------------------------------------- |
| **Backend**   | Python, Django                                 |
| **Frontend**  | HTML, Bootstrap 4                              |
| **Database**  | SQLite3                                        |
| **Libraries** | Pillow, django-crispy-forms, crispy-bootstrap4 |

---

## 📁 Project Structure

```plaintext
BLOG/
│── .venv/                 # Virtual environment
│── assignments/           # Additional project resources
│── blog_main/             # Main Django project configuration
│── blogs/                 # Blog app for posts and categories
│── dashboards/            # Admin and user dashboard app
│── media/                 # Uploaded images and files
│── templates/             # Global HTML templates
│── .gitignore             # Git ignored files
│── db.sqlite3             # SQLite database
│── manage.py              # Django management script
│── readme.md              # Project documentation
│── requirements.txt       # Project dependencies
```

---

## ⚙️ Installation and Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Datta-6699/BLOG.git
cd BLOG
```

### 2️⃣ Create and Activate a Virtual Environment

```bash
python -m venv .venv
```

**Windows:**

```bash
.venv\Scripts\activate
```

**Mac/Linux:**

```bash
source .venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If needed, install manually:

```bash
pip install django pillow django-crispy-forms crispy-bootstrap4
```

### 4️⃣ Apply Database Migrations

```bash
python manage.py migrate
```

### 5️⃣ Create a Superuser

```bash
python manage.py createsuperuser
```

### 6️⃣ Run the Development Server

```bash
python manage.py runserver
```

Visit the application:

* **Homepage:** http://127.0.0.1:8000/
* **Admin Panel:** http://127.0.0.1:8000/admin/

---

## 📦 Dependencies

```txt
Django
Pillow
django-crispy-forms
crispy-bootstrap4
```

Generate automatically using:

```bash
pip freeze > requirements.txt
```

---

## 🔮 Future Enhancements

* Rich text editor integration (CKEditor or TinyMCE)
* Django REST Framework (DRF) APIs
* PostgreSQL for production deployment
* Social media sharing
* Email notifications and newsletters
* Dark mode support
* Tagging and bookmarking features

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to GitHub:

   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## 👨‍💻 Author

**Sri Datta Undavalli**
🔗 GitHub: https://github.com/Datta-6699

---

⭐ If you found this project helpful, please consider giving it a star on GitHub!
