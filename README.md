# Django-blog-tutorial

This is a simple blog application using Python and Django. Its main features are:

- User authentication
- Blog post creation and display
- Group-based permissions (e.g., "Editors" can edit posts)
- Use of Django templates and static files (CSS, images)
- Admin interface for managing content

## Features

- Home page listing all blog posts
- Individual post detail pages
- Admin panel for creating, editing, and deleting posts
- Group-based access control for editing posts
- Responsive design with custom CSS

## Technologies Used

- Python 3
- Django 5.2
- SQLite (default development database)
- HTML, CSS

- ## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```

4. **Create a superuser (for admin access):**
   ```sh
   python manage.py createsuperuser
   ```

5. **Run the development server:**
   ```sh
   python manage.py runserver
   ```
6. **Access the app:**
   - Blog: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
   - Admin: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
  
## Screenshots

![Blog Home Page](https://github.com/CodeHarold/Django-blog-tutorial/blob/main/tutorial/screenshots/homePage.png)
![Post1](https://github.com/CodeHarold/Django-blog-tutorial/blob/main/tutorial/screenshots/post1.png)


