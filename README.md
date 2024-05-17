# React + Vite

Project Title:
Netflix-Inspired Streaming Platform

Description

This project is a Netflix-inspired streaming platform built using React.js and Firebase. It allows users to browse movie details fetched from The Movie Database (TMDB) API. Additionally, it features user authentication through Firebase, enabling users to create accounts and log in to the site.
Features

    Movie Browsing: Browse and view details of movies from TMDB API.
    User Authentication: Create an account and log in using Firebase Authentication.
    Responsive Design: Fully responsive design that works on both desktop and mobile devices.

Technologies Used

    Frontend: React.js
    Backend: Firebase
    API: The Movie Database (TMDB) API
    Authentication: Firebase Authentication

Installation

    Clone the repository:

    bash

git   https://netflix-clone-website.netlify.app/

Navigate to the project directory:

bash

cd netflix-inspired-platform

Install dependencies:

bash

npm install

Create a .env file in the root directory and add your TMDB API key and Firebase configuration:

env

REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_firebase_app_id

Start the development server:

bash

    npm start

Usage

    Browse Movies: Browse and search for movies using the TMDB API.
    User Authentication: Create an account or log in to save your favorite movies.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
License

This project is licensed under the MIT License.

Contact
For any inquiries or support, please contact vinay.kopperakumar@gmail.com.




This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
