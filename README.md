# Fullstack Chat App

This is a fullstack chat application built with React, Vite, Express, MongoDB, and Socket.io. The application allows users to sign up, log in, update their profile, and chat with other users in real-time.

## Features

- User authentication (signup, login, logout)
- Real-time messaging with Socket.io
- Profile picture upload with Cloudinary
- Protected routes with JWT authentication
- Responsive design with Tailwind CSS and DaisyUI
- Theme customization

## Project Structure
Workspace
(rerun without)
Searching 2 directories for "create a README file"…

Collecting workspace information

Sure, here is a README file for your project:

. ├── backend │ ├── .env │ ├── package.json │ ├── src │ │ ├── controllers │ │ │ ├── auth.controller.js │ │ │ └── message.controller.js │ │ ├── index.js │ │ ├── lib │ │ │ ├── cloudinary.js │ │ │ ├── db.js │ │ │ ├── socket.js │ │ │ └── utils.js │ │ ├── middleware │ │ │ └── auth.middleware.js │ │ ├── models │ │ │ ├── message.model.js │ │ │ └── user.model.js │ │ ├── routes │ │ │ ├── auth.route.js │ │ │ └── message.route.js │ │ └── seeds │ │ └── user.seed.js ├── frontend │ ├── eslint.config.js │ ├── index.html │ ├── package.json │ ├── postcss.config.js │ ├── public │ ├── README.md │ ├── src │ │ ├── App.jsx │ │ ├── components │ │ │ ├── AuthImagePattern.jsx │ │ │ ├── ChatContainer.jsx │ │ │ ├── ChatHeader.jsx │ │ │ ├── MessageInput.jsx │ │ │ ├── Navbar.jsx │ │ │ ├── NoChatSelected.jsx │ │ │ └── Sidebar.jsx │ │ ├── constants │ │ ├── index.css │ │ ├── lib │ │ │ ├── axios.js │ │ │ └── utils.js │ │ ├── main.jsx │ │ ├── pages │ │ │ ├── HomePage.jsx │ │ │ ├── LoginPage.jsx │ │ │ ├── ProfilePage.jsx │ │ │ └── SettingsPage.jsx │ │ │ └── SignUpPage.jsx │ │ ├── store │ │ │ ├── useAuthStore.js │ │ │ ├── useChatStore.js │ │ │ └── useThemeStore.js │ ├── tailwind.config.js │ └── vite.config.js ├── .gitignore └── package.json
