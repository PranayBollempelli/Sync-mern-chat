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

## Table of Contents

*   [Backend](#backend)
*   [Frontend](#frontend)
*   [Development Setup](#development-setup)
*   [Contributing](#contributing)
*   [License](#license)

## Backend (`backend` directory)

*   `.env` - Environment variables for development and potentially production configurations.
*   `package.json` - Project dependencies and scripts for the backend.
*   `src` - Source code for the backend application:
    *   `controllers` - Controllers for handling API requests.
        *   `auth.controller.js`
        *   `message.controller.js`
    *   `index.js` - Entry point for the backend application.
    *   `lib` - Utility libraries used throughout the backend.
        *   `cloudinary.js` - Cloudinary integration.
        *   `db.js` - Database connection and setup.
        *   `socket.js` - Socket.IO setup (if applicable).
        *   `utils.js` - General utility functions.
    *   `middleware` - Middleware functions for authentication, authorization, etc.
        *   `auth.middleware.js` - Authentication middleware.
    *   `models` - Data models representing database entities.
        *   `message.model.js` - Message data model.
        *   `user.model.js` - User data model.
    *   `routes` - API endpoints defined for the backend.
        *   `auth.route.js` - Authentication routes.
        *   `message.route.js` - Message routes.
    *   `seeds` - Seed data for populating the database during development.
        *   `user.seed.js` - User seed data.

## Frontend (`frontend` directory)

*   `eslint.config.js` - Configuration for the ESLint linter, ensuring code quality.
*   `index.html` - The main HTML entry point for the frontend application.
*   `package.json` - Project dependencies and scripts for the frontend.
*   `postcss.config.js` - Configuration for handling CSS preprocessors.
*   `public` - Static assets accessible directly by the browser.
*   `src` - Source code for the frontend application:
    *   `App.jsx` - The root component of the frontend application.
    *   `components` - Reusable UI components for building the frontend.
        *   `AuthImagePattern.jsx`
        *   `ChatContainer.jsx`
        *   `ChatHeader.jsx`
        *   `MessageInput.jsx`
        *   `Navbar.jsx`
        *   `NoChatSelected.jsx`
        *   `Sidebar.jsx`
    *   `constants` - Global constants used throughout the frontend.
    *   `index.css` - Global CSS styles for the frontend.
    *   `lib` - Utility libraries used throughout the frontend.
        *   `axios.js` - Axios HTTP client setup.
        *   `utils.js` - General utility functions.
    *   `main.jsx` - The entry point for the frontend application.
    *   `pages` - Individual pages of the application.
        *   `HomePage.jsx`
        *   `LoginPage.jsx`
        *   `ProfilePage.jsx`
        *   `SettingsPage.jsx`
        *   `SignUpPage.jsx`
    *   `store` - State management (e.g., using Redux, Context API, or Zustand).
        *   `useAuthStore.js`
        *   `useChatStore.js`
        *   `useThemeStore.js`
    *   `tailwind.config.js` - Configuration for the Tailwind CSS utility framework.
*   `vite.config.js` - Configuration for the Vite development server.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/fullstack-chat-app.git
cd fullstack-chat-app
```

## Development Setup

1.  **Prerequisites:**
    *   Node.js and npm (or yarn) installed on your system.

2.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/your-repo.git](https://github.com/your-username/your-repo.git)
    cd your-repo
    ```

3.  **Install dependencies:**

    *   For both backend and frontend (if applicable):

        ```bash
        npm install  # or yarn install
        ```

4.  **Run the application:**

    *   **Backend:** Refer to the specific scripts defined in `backend/package.json` to start the backend server (e.g., `npm run dev` or `npm start`).
    *   **Frontend:** Refer to the specific scripts defined in `frontend/package.json` to start the development server (e.g., `npm run dev` or `npm start`).

## License

Specify the license under which your project is distributed (e.g., MIT, Apache, etc.).

