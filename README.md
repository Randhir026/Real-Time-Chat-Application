
# Real-Time Chat Application

A real-time chat application built using **Django**, **Django Channels**, and **WebSockets** that enables users to communicate instantly without refreshing the page.

## 🚀 Features

* User Registration
* User Login & Logout
* Real-Time Messaging
* WebSocket Communication
* Django Channels Integration
* Responsive User Interface
* Session-Based Authentication

## 🛠️ Tech Stack

* Python
* Django
* Django Channels
* WebSockets
* HTML5
* CSS3
* JavaScript
* SQLite

## 📂 Project Structure

```text
chatproject/
│
├── chat/
│   ├── templates/
│   │   └── chat/
│   │       ├── base.html
│   │       ├── chat_room.html
│   │       ├── login.html
│   │       ├── logout.html
│   │       └── register.html
│   │
│   ├── admin.py
│   ├── apps.py
│   ├── consumers.py
│   ├── models.py
│   ├── routing.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── chatproject/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/randhir026/django-realtime-chat-app.git
cd django-realtime-chat-app
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Database Migrations

```bash
python manage.py migrate
```

### Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

### Start Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## 🔧 Future Improvements

* Group Chat Support
* Private Messaging
* Message History Storage
* Typing Indicators
* Online/Offline User Status
* File Sharing
* Emoji Support


## 📚 Learning Outcomes

* Django Channels and ASGI
* WebSocket Communication
* Real-Time Event Handling
* Authentication and Session Management
* Debugging Distributed Systems

## 👨‍💻 Author

**Randhir Kumar**

* Python Developer
* AI/ML Enthusiast
* Django Developer

Feel free to contribute, raise issues, or suggest improvements.
