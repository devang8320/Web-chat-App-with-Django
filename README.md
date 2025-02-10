# 🌐 WebChat - Real-Time Messaging Application

Welcome to **WebChat**, a modern real-time messaging application designed for seamless communication. With an intuitive interface and robust backend, WebChat offers a feature-rich chatting experience.


## 🎯 Features

### 🔐 Authentication

✅ **User Registration & Login** - Secure authentication with Django backend.\
✅ **Session Management** - Persistent user sessions for a seamless experience.

### 💬 Chat Functionality

✅ **Group Chat** - Create and join group conversations for seamless communication.

✅ **One-on-One Messaging** - Private real-time conversations.\
✅ **Typing Indicators** - See when the other user is typing.\
✅ **Online Status** - Displays active and offline users.\
✅ **Emoji Support** - Express emotions with a variety of emojis.\
✅ **Read Receipts** - Know when your message has been seen.

### ⚡ Real-Time Capabilities

✅ **WebSockets for Live Chat** - Instant message delivery using Django Channels.\
✅ **Live Notifications** - Get notified of new messages and online users.

### 🖥️ User Interface

✅ **Responsive Design** - Optimized for desktop and mobile.\
✅ **Dark/Light Mode** - Customize your chat experience.

---

## 🏗️ Technology Stack

| Category           | Technologies                    |
| ------------------ | ------------------------------- |
| **Frontend**       | React.js                        |
| **Backend**        | Django, Django Channels         |
| **Database**       | PostgreSQL                      |
| **WebSockets**     | Django Channels, WebSockets API |
| **Authentication** | JWT, Django Auth                |

---

## 📖 Project Overview

WebChat is built with a **Django backend** and **React frontend**, leveraging **WebSockets** for real-time messaging. The application features secure authentication, interactive messaging, and live notifications, ensuring an engaging user experience.

Key highlights:

- **Scalable real-time chat** powered by Django Channels.
- **Modern UI with responsive design** using React.
- **Secure and efficient** authentication with JWT.
- **Optimized for performance and usability** with WebSockets.

---

## 🚀 Installation & Setup

### 🔧 Backend (Django)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/webchat.git
   cd webchat
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash


   # If not, install dependencies manually:
   pip install django djangorestframework channels
   ```
4. Run database migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the Django server:
   ```bash
   python manage.py runserver
   ```

### 🖥️ Frontend (React)

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

---

## 📬 Contact

For any questions or collaboration opportunities, feel free to reach out:

👤 **Name:** Devang Vasani\
📧 **Email:** [devangvasani8320@gmail.com](mailto\:devangvasani8320@gmail.com)

---

💡 *Built with passion to revolutionize real-time communication!* 🚀

Additionally, WebChat supports **group chat** functionality, enabling users to communicate in shared spaces seamlessly. The project also includes a `requirements.txt` file for easy dependency management.

