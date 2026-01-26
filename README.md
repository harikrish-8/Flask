# Flask CRUD - Student Management

A simple, clean Flask web application for managing student records with full CRUD (Create, Read, Update, Delete) functionality. Perfect for learning Flask basics and web application fundamentals.

## Features

- ✅ **Add Students** - Create new student records with name and age
- ✅ **View Students** - Display all students in a responsive table
- ✅ **Update Students** - Edit student information inline
- ✅ **Delete Students** - Remove students with confirmation dialog
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- 💾 **In-Memory Storage** - Simple list-based data storage (no database required)

## Project Structure

```
Flask/
├── app.py                 # Flask application with CRUD routes
├── README.md             # Project documentation
├── templates/
│   └── index.html        # Main HTML template
└── static/
    ├── css/
    │   └── styles.css    # Styling and responsive design
    └── js/
        └── script.js     # Delete confirmation handler
```

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Setup

1. **Clone or download this repository**

2. **Install Flask**
   ```bash
   pip install flask
   ```

3. **Navigate to the project directory**
   ```bash
   cd "j:\Domain X labs\Flask"
   ```

## Running the Application

1. **Start the Flask server**
   ```bash
   python app.py
   ```

2. **Open your browser** and navigate to:
   ```
   http://localhost:5000
   ```

3. **Start managing students!** Add, edit, and delete records using the web interface.

## How It Works

### Backend (Flask Routes)

- **`GET /`** - Displays the main page with all students
- **`POST /add`** - Adds a new student (form submission)
- **`POST /update/<id>`** - Updates an existing student's information
- **`GET /delete/<id>`** - Deletes a student from the list

### Frontend

- **Add Form** - Simple inputs for student name and age
- **Student Table** - Displays all records with inline editing
- **Actions** - Update and Delete buttons with delete confirmation

### Data Storage

Students are stored in a Python list in memory. This means:
- Data is lost when the server stops
- Perfect for learning and demonstrations
- No database setup required

## Technologies Used

- **Backend**: Flask (Python web framework)
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Modern CSS with responsive design
- **Fonts**: Google Fonts (Manrope)

## Future Enhancements

Consider adding:
- Database integration (SQLite, PostgreSQL, etc.)
- User authentication
- Data persistence (save/load from file)
- Student search and filtering
- Export functionality (PDF, CSV)
- Form validation and error handling
- API endpoints (JSON responses)

## Notes

- This is a learning project designed to demonstrate Flask CRUD fundamentals
- In-memory storage means data is reset when the server restarts
- The application runs in debug mode by default for easy development