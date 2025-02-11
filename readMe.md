# ToDoGemini

ToDoGemini is a **task management application** built with **Python**, **FastAPI**, **SQLAlchemy**, and **MySQL**. It provides an intuitive way for users to create, update, and manage their to-do lists with an interactive web interface.

## 🚀 Features

- 📝 **Task Management**: Create, edit, update, and delete tasks.
- 🔐 **Authentication & Authorization**: User login and registration with JWT-based authentication.
- 🌐 **Interactive Web Interface**: Built with **HTML, CSS, Bootstrap, and JavaScript**.
- 🤖 **AI-enhanced Descriptions**: Uses **Gemini AI** to generate detailed task descriptions.
- 🗄 **Database Integration**: Uses **MySQL with SQLAlchemy ORM**.
- 🏗 **Docker Support**: Easily deployable using **Docker** and `docker-compose`.

---

## 🛠 Technologies Used

- **Backend:** Python, FastAPI, SQLAlchemy
- **Database:** MySQL
- **Authentication:** JWT (JSON Web Token)
- **AI Integration:** Gemini AI (Google Generative AI)
- **Containerization:** Docker, Docker Compose
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Others:** bcrypt, passlib, python-dotenv

---

## 📦 Installation & Setup

### Clone the Repository & Install Dependencies

```bash
git clone https://github.com/EcemKonca/ToDoGemini.git
cd ToDoGemini
pip install -r requirements.txt
```

### Run the Application
```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```
Access the application at: http://localhost:8000

### (Optional) Run with Docker
```bash
docker-compose up --build
```
