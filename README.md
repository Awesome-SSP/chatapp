# 💬 ChatApp

ChatApp is a real-time messaging web application built using Django. It allows users to register, log in, and engage in live conversations with other users. The app features a user-friendly interface, real-time updates via WebSockets (Django Channels), and scalable architecture.

---

## 🚀 Features

- 🔐 User Authentication (Register/Login/Logout)
- 💬 One-to-One and Group Chat Support
- 📡 Real-time Messaging using Django Channels & WebSockets
- 🧠 Message History and Persistence
- 🔔 Live Typing Indicator (optional)
- 🌙 Responsive UI with light/dark theme toggle (optional)

---

## 🛠 Tech Stack

- **Backend:** Django, Django Channels, Redis (for WebSocket handling)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap or Tailwind CSS
- **Database:** SQLite (default) or PostgreSQL (for production)
- **Deployment:** Docker, Gunicorn, Daphne, Nginx

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Awesome-SSP/chatapp.git
cd chatapp
```

### 2. Create a Virtual Environment

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up the Database

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser

```bash
python manage.py createsuperuser
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

---

## 📁 Project Structure

```
chatapp/
├── chat/               # Chat logic (models, consumers, views)
├── users/              # Authentication and user management
├── templates/          # HTML templates
├── static/             # Static files (CSS, JS)
├── chatapp/            # Main Django project settings
├── manage.py
└── requirements.txt
```

---

## 📸 Screenshots

> Add relevant screenshots of chat interface, login screen, etc.

---

## 🧪 Running Tests

```bash
python manage.py test
```

---

## 🚢 Deployment

Use platforms like **Render**, **Heroku**, or **DigitalOcean** for deployment. Make sure to:

- Use PostgreSQL in production.
- Configure Daphne or ASGI server.
- Set up Redis for channels layer.
- Set environment variables for `SECRET_KEY`, `DEBUG=False`, etc.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

Made with ❤️ by Awesome-SSP

- [@SSP](https://github.com/Awesome-SSP)

## Support

For support, you can buy me a coffee

<a href="https://buymeacoffee.com/i.awesomessp" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
