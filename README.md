# BLOG
Django Blogging Platform

This repository contains the source code for a full-featured blogging platform built with the Django web framework. It includes a complete content management system, user authentication, a management dashboard, and a responsive public-facing site.

Key Features
Content Management: Full CRUD (Create, Read, Update, Delete) functionality for blog posts and categories via a secure dashboard.
User Administration: A dashboard for superusers to manage site users, including adding, editing, and deleting user accounts and assigning permissions.
Dynamic Frontend:
A homepage showcasing featured and recent posts.
The ability to filter posts by category.
A full-text search engine to find articles by keyword.
Detailed post view with an authenticated commenting system.
Authentication & Authorization:
User registration, login, and logout capabilities.
Permission-based access control for dashboard views and actions.
Automatic Slug Generation: Unique, SEO-friendly slugs are automatically created for each blog post.
Media Handling: Support for uploading and displaying featured images for blog posts.
Tech Stack
Backend: Python, Django
Frontend: HTML, Bootstrap 4
Database: SQLite3
Libraries:
Pillow for image processing.
django-crispy-forms and crispy-bootstrap4 for elegant form rendering.
Local Setup and Installation
Follow these steps to run the project on your local machine.

Clone the Repository

git clone https://github.com/datta-6699/BLOG.git
cd BLOG
Create and Activate a Virtual Environment

On macOS/Linux:
python3 -m venv venv
source venv/bin/activate
On Windows:
python -m venv venv
.\venv\Scripts\activate
Install Dependencies

pip install -r requirements.txt
Apply Database Migrations

python manage.py migrate
Create a Superuser

You will need a superuser account to access the admin panel and the management dashboard.

python manage.py createsuperuser
Follow the prompts to create a username and password.

Run the Development Server

python manage.py runserver
The application will be available at http://127.0.0.1:8000/. The Django admin panel is at http://127.0.0.1:8000/admin/.

Project Structure
The repository is organized into several Django applications:

blog_main: The main project package containing settings, root URL configuration (urls.py), and global static files.
blogs: Manages the core blogging models (Blog, Category, Comment) and the public-facing views for displaying posts, categories, and search results.
dashboards: Contains the views, forms, and templates for the user dashboard, which handles all administrative CRUD operations for posts, categories, and users.
assignments: A supplementary app for managing site-wide content, such as the "About" section and SocialLink models.
templates: A top-level directory containing all HTML templates for the project.
media: The directory where user-uploaded files, such as post images, are stored.
