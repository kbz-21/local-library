# Local Library

Local Library is a web-based application built with Django for managing books, authors, genres, and book availability. It allows users to browse books, view details, and manage library resources efficiently.

## Features
- Add, update, and delete books, authors, and genres
- Track book availability and loan status
- User authentication for managing resources
- Search and filter books by title, author, or genre
- Admin interface for easy content management

## Technologies Used
- **Backend:** Django (Python)
- **Database:** SQLite (default), can be configured for PostgreSQL, MySQL, etc.
- **Frontend:** HTML, CSS, JavaScript (with Django templates)

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/local-library.git
   cd local-library
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser (for Admin Panel):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the Application:**
   - Local Library: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
   - Admin Panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

## Project Structure
```
local-library/
├── library/             # Main Django app
├── templates/           # HTML templates
├── static/              # Static files (CSS, JS)
├── manage.py            # Django management script
└── requirements.txt     # Python dependencies
```

## Contributing
1. Fork the repository
2. Create your feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request

## License
This project is licensed under the MIT License.

## Contact
For questions or support, please contact [your-email@example.com].

