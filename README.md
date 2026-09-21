Event Management System

A full-stack web application designed to simplify the creation, management, discovery, and registration of college events.

🚀 Tech Stack

Frontend

- HTML
- CSS
- JavaScript

Backend

- Python
- FastAPI
- SQLAlchemy

Database

- PostgreSQL

Tools

- Git
- GitHub

✨ Features

- 🔐 User authentication
- 👨‍🎓 Student and organizer roles
- 📅 Create and manage events
- 🔎 Browse available events
- 📝 Register for events
- 👤 Role-based access
- 🗄️ PostgreSQL database
- 🔒 Password hashing and secure authentication

👥 User Roles

Student

- Register and log in
- Browse events
- View event details
- Register for events

Organizer

- Register and log in
- Create events
- Update events
- Delete events
- Manage event information

📁 Project Structure

event-management/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── auth.py
│   └── ...
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── ...
│
├── .gitignore
├── README.md
└── requirements.txt

«The project structure may change as development progresses.»

⚙️ Getting Started

1. Clone the repository

git clone <repository-url>
cd event-management

2. Create a virtual environment

python -m venv venv

Activate it:

Windows:

venv\Scripts\activate

Linux/macOS:

source venv/bin/activate

3. Install dependencies

pip install -r requirements.txt

4. Configure environment variables

Create a ".env" file and add your database and authentication configuration.

DATABASE_URL=your_postgresql_database_url
SECRET_KEY=your_secret_key

Do not commit ".env" to GitHub.

5. Run the FastAPI server

uvicorn main:app --reload

The API will be available at:

http://127.0.0.1:8000

FastAPI documentation:

http://127.0.0.1:8000/docs

🌿 Git Workflow

Each team member should work on their own feature branch.

git checkout -b feature/your-feature

After completing the feature:

git add .
git commit -m "Add your feature"
git push origin feature/your-feature

Create a Pull Request to merge the feature into the main branch.

🎯 Project Goal

The goal of this project is to provide a centralized platform for managing college events and making event registration easier for students and organizers.

📌 Project Status

🚧 Under Development

More features and improvements will be added as development progresses.

👨‍💻 Contributors

This project is developed as a college group project.

- Member 1 — Backend / Authentication
- Member 2 — Frontend
- Member 3 — Event Management
- Member 4 — Event Registration
- Member 5 — Testing / Integration
- Coordinator — Project coordination and integration

📄 License

This project is developed for educational purposes.
