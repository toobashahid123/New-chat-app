**Chat Application**


**Overview**
This is a real-time chat application built with Django and WebSockets. The application allows users to join chat rooms and communicate with each other in real-time. It is designed to demonstrate the use of Django channels for handling WebSocket connections and real-time data transfer.

**Features**
Real-time Messaging: Instant messaging using WebSockets.
Chat Rooms: Users can create and join different chat rooms.
Responsive Design: Mobile-friendly interface for easy access on all devices.

**Technologies Used**
Django: Python web framework for building the backend.
Django Channels: Extension for handling WebSocket connections.
SQLite: Database for storing user information and chat logs.
HTML/CSS: Frontend design and layout.
JavaScript: For handling real-time updates and client-side logic.



**Installation**

**Prerequisites**
Python 3.8+
Virtualenv (optional but recommended)
Git

**Setup Instructions**
Clone the repository:
git clone https://github.com/toobashahid123/New-chat-app.git

**Create a virtual environment (optional)**
python -m venv venv
source venv/bin/activate

**Install the required dependencies**
pip install -r requirements.txt

**Apply migrations and Run the development server**
python manage.py migrate
python manage.py runserver

**Access the application**
Open your web browser and go to http://127.0.0.1:8000/


**Usage**
1-Join/Create Chat Rooms: Enter a chat room name to join or create a new room.
2-Chat: Start sending and receiving messages in real-time.

**Contributing**
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and passes all tests.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contact**
For any inquiries or issues, please contact:

Name: Tooba Shahid
Email: tooba7987@gmail.com
GitHub: toobashahid123

**Project Structure**
├── chatApp
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__
├── chat
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── consumers.py
│   ├── models.py
│   ├── routing.py
│   ├── templates
│   │   └── chat
│   │       ├── index.html
│   │       └── room.html
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── __pycache__
├── db.sqlite3
├── manage.py
└── requirements.txt





