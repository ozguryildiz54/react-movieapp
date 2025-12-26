# React Movie App

A React + Tailwind CSS movie discovery app powered by the TMDB API, with Firebase Authentication (Email/Password + Google).

## Demo
![Movie App Demo](./movie.gif)

## Features
- Browse movies (popular/discover)
- Search movies by title
- Movie detail page (poster, overview, rating, etc.)
- Firebase Auth:
  - Email/Password login & register
  - Google Sign-In
- Protected routes (requires login)

## Tech Stack
- React (Create React App)
- React Router
- Tailwind CSS
- Firebase Authentication
- TMDB API

## Project Structure (src/)
- `assets/icons/` icons & static assets
- `auth/` Firebase auth/config helpers
- `components/` reusable UI components
- `context/` global state (Auth context)
- `helpers/` utility functions (API helpers, constants)
- `pages/` pages (Home, Detail, Login, Register, etc.)
- `router/` routes + protected route logic
- `App.js` app shell
- `index.js` entry

---

# Run Locally (3 Steps)

## 1) Install
```bash
git clone https://github.com/ozguryildiz54/react-movieapp.git
cd react-movieapp
npm install
2) Create .env (IMPORTANT)
Create a file named .env in the project root (same folder as package.json, NOT inside src).

Path must look like:

bash
react-movieapp/.env
react-movieapp/package.json
react-movieapp/src/
Put this inside .env:

env
# TMDB
REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here

# Firebase (Auth)
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_firebase_sender_id
REACT_APP_FIREBASE_APP_ID=your_firebase_app_id
3) Run
bash
npm start
Open:

http://localhost:3000

Scripts
bash
npm start
npm run build
npm test
Roadmap
Pagination / infinite scroll

Favorites / watchlist

Loading skeletons + better error handling

Basic tests (React Testing Library)

Author
Özgür Yıldız
GitHub: https://github.com/ozguryildiz54
LinkedIn: https://linkedin.com/in/ozguryildiz0
