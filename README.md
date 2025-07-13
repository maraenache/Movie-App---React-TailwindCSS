# 🎬 Movie Search & Trending App
YouTube link : [Movie App React](https://youtu.be/heAWBq6kZnc)

A fast, responsive React app to search movies and discover trending titles based on real user data.
This React-based project allows users to search for movies using the **TMDb API** and displays detailed movie information in a sleek, responsive UI powered by **Tailwind CSS**. It features smart performance improvements like **debounced input** to reduce unnecessary API calls and includes a trending section generated from backend-stored search data, showcasing the most popular movies dynamically.

---

## Overview

This app lets users search movies via the TMDb API with debounced input to minimize API calls. It tracks user searches by sending queries to an Appwrite backend, which aggregates the data to display trending movies in real-time. The interface is built with Tailwind CSS for a clean, modern look and powered by Vite for rapid development and lightning-fast builds.

---

## Features

- **Debounced search input** — reduces unnecessary API requests  
- **TMDb API integration** — fetches movie data dynamically using native Fetch API  
- **Trending movies** — generated from real user searches stored in Appwrite  
- **Responsive UI** — styled with Tailwind CSS for mobile & desktop  
- **Modular React components** — clean and maintainable codebase  
- **Powered by Vite** — ultra-fast development experience  
- **Optional React Query support** — for data caching and smooth state management  

---

## Technologies

| Tech          | Role                                   |
|---------------|--------------------------------------|
| React         | UI library                           |
| Vite          | Dev server and build tool            |
| Tailwind CSS  | Styling framework                    |
| TMDb API      | Movie database API                   |
| Fetch API     | Native HTTP requests                 |
| use-debounce  | Debouncing input                     |
| Appwrite      | Backend for analytics & trending data|
| React Query   | (Optional) data fetching & caching  |

---
## ⚙️ How It Works

1. **User types a movie name** in the search input.
2. Input is **debounced** (500ms delay) before triggering an API request to TMDb.
3. Results display instantly in a clean, scrollable list with key movie info.
4. User searches are **tracked and stored** on Appwrite backend.
5. The **Trending Movies** carousel dynamically updates based on stored search popularity.
6. Entire UI is styled with Tailwind CSS for fast, responsive rendering.

## Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/movie-search-app.git
   cd movie-search-app
