# 🎬 MovieBase

A modern, responsive movie discovery application built with React, Appwrite, and the TMDB API. Search, explore trending films, and experience a sleek UI crafted for all movie lovers.

---

## 📚 Table of Contents

- 🤖 Introduction  
- ⚙️ Tech Stack  
- 🔋 Features  
- 🚀 Quick Start  
- 🧩 Snippets  
- 🔗 Assets  
- 📺 More  
- 🤝 Contributing  
- 👨‍💻 Author

---

## 🤖 Introduction

**MovieBase** is a sleek React-based application that allows users to explore popular and trending movies using the [TMDB API](https://developer.themoviedb.org/). It integrates [Appwrite](https://appwrite.io) for backend services such as data storage and analytics. Built with **Tailwind CSS** and **Vite**, the app ensures a fast, responsive, and elegant user experience.

Whether you're just browsing or searching for a specific title, MovieBase offers a smooth and interactive platform to find movies you'll enjoy — without the hassle.

---

## ⚙️ Tech Stack

- **React.js** – Component-based UI framework by Meta  
- **Appwrite** – Backend-as-a-Service for storing trending data  
- **TMDB API** – Fetches live movie data  
- **Tailwind CSS** – Utility-first CSS framework for responsive styling  
- **React-use** – Simplifies hooks for debounced search functionality  
- **Vite** – Lightning-fast development and build tool  

---

## 🔋 Features

- 🔍 **Live Search** – Search movies as you type with debounced requests  
- 🎥 **Trending Section** – Displays a dynamic list of trending movies (Appwrite-powered)  
- 🧠 **TMDB Integration** – Real-time results using The Movie Database API  
- 📱 **Responsive Design** – Works perfectly on mobile, tablet, and desktop  
- ⚡ **Fast Loading** – Built using Vite for optimal dev and build performance  
- 🔁 **Reusable Components** – Clean, modular architecture with maintainable code  

---

## 🚀 Quick Start

### 🔧 Prerequisites

Make sure you have the following installed:

- Git  
- Node.js  
- npm  

### 📥 Clone the Repository, Install & Run

```bash
# Clone the repository
git clone https://github.com/arpit-negi/MovieBase.git
cd MovieBase

# Install dependencies
npm install

# Create a `.env.local` file in the root directory and add:
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id

# Replace the above placeholders with your actual TMDB and Appwrite credentials

# Start the development server
npm run dev

# Open in your browser:
http://localhost:5173
```

---

## 🧩 Snippets

Useful components and utilities used in the project:

- `components/Search.jsx` – Reusable search input with state control  
- `components/Spinner.jsx` – Custom loading spinner  
- `components/MovieCard.jsx` – UI for rendering each movie  
- `appwrite.js` – Handles Appwrite integration  
- `useDebounce` – Debounced hook using `react-use` for smoother UX  

---

## 🔗 Assets

- TMDB official logo & API: [https://developer.themoviedb.org/](https://developer.themoviedb.org/)  
- Appwrite: [https://appwrite.io](https://appwrite.io)

---

## 📺 More

Want to improve or add new features? Here are a few ideas to extend MovieBase:

- 🔐 Add Auth using Appwrite  
- 📝 Allow users to save favorite movies  
- 💬 Integrate movie reviews or trailers  
- 🌍 Add multi-language support  
- 🎨 Theme toggle (dark/light)

---

## 🤝 Contributing

Have ideas or found a bug? Feel free to open an issue or submit a pull request. Contributions are always welcome!

---

## 👨‍💻 Author

Created by [@arpit-negi](https://github.com/arpit-negi)  
Built with ❤️ and a passion for clean design, modern tooling, and movies.
