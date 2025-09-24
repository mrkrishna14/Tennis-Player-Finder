# Tennis Player Finder

A Flask web application that helps tennis players connect with each other based on age and skill level. Users can register, login, and find compatible tennis partners in their area.

## Features

- User authentication (registration and login)
- Secure password hashing with bcrypt
- Player matching based on age and skill level
- Clean, responsive web interface
- SQLite database for data persistence

## Technologies Used

- **Backend**: Flask (Python web framework)
- **Database**: SQLite with SQLAlchemy ORM
- **Authentication**: Flask-Login with bcrypt password hashing
- **Forms**: Flask-WTF with WTForms
- **Frontend**: HTML, CSS

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Tennis-Player-Finder
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
cd "Tennis FInder"
python tennis.py
```

4. Open your browser and navigate to `http://localhost:5000`

## Usage

1. **Register**: Create a new account with a username and password
2. **Login**: Sign in with your credentials
3. **Find Matches**: Enter your name, age, and skill level to find compatible tennis partners
4. **Browse Results**: View other players who match your criteria

## Project Structure

```
Tennis-Player-Finder/
├── Tennis FInder/
│   ├── tennis.py          # Main Flask application
│   ├── templates/         # HTML templates
│   │   ├── home.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── dashboard.html
│   │   └── match.html
│   └── static/           # CSS and static files
├── requirements.txt       # Python dependencies
└── README.md            # This file
```

## Security Notes

- Passwords are securely hashed using bcrypt
- User sessions are managed securely with Flask-Login
- Database files are excluded from version control via .gitignore

## Future Enhancements

- Location-based matching
- Real-time messaging between players
- Tournament organization features
- Mobile-responsive design improvements
