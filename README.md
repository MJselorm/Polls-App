# Polls-App
A simple web app that lets users create, vote, and view polls in real-time. Built with Django for backend logic and Bootstrap for a clean, responsive interface.

---

## 🚀 Features
- 🧾 Create and manage multiple polls
- 🗳️ Vote for your preferred options
- 📊 View live poll results with percentages
- 🔒 Optional user authentication (login & register)
- ⚡ Built with Django’s MVC (Model–View–Controller) pattern

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3, Bootstrap
- **Database:** SQLite (default) or PostgreSQL
- **Version Control:** Git & GitHub

---

## 💡 How It Works
1. A user creates a poll with one or more options.
2. Visitors can vote once per poll.
3. Results are displayed instantly with dynamic updates.

---

## 🖥️ Setup & Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/polls-app.git
cd polls-app

# Create virtual environment
python -m venv venv
source venv/bin/activate  # on Mac/Linux
venv\Scripts\activate     # on Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver