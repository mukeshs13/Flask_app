
# Flask Web Application  
A simple Flask web application with user authentication and database integration.

## Project Description  
This project implements a basic web application using Flask, supporting:

- User authentication (Login & Registration)  
- Persistent data storage with SQLite (`database.db`)  
- Dynamic HTML templates (Jinja2)  

---

## Project Structure  
```
📦 flask-web-app
├── 📂 templates
│    ├── login.html          # User login page
│    ├── register.html       # User registration page
│    └── dashboard.html      # User dashboard (after login)
├── app.py                   # Main Flask application (routes)
├── models.py                # Database models and schema
└── 📂 instance
     └── database.db         # Auto-generated SQLite database
```

---

## Installation Instructions  

1. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies:**
   ```bash
   pip install Flask
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```

4. **Access the application:**
   ```
   http://localhost:5000
   ```

---

## Usage  
- **Register**: Create a new user account.  
- **Login**: Access the dashboard after successful authentication.  
- **Dashboard**: View protected content after logging in.  

---

## Contributing  
1. Create a new branch (`feature-branch`).  
2. Commit your changes.  
3. Open a pull request.  

---
