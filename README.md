📽️ Mini Movie Explorer – Project Overview & Approach
🔍 Overview
Mini Movie Explorer is a responsive, single-page web application that allows users to:

Search movies using the OMDb API

Add/remove movies to a personalized watchlist (stored in localStorage)

Toggle between dark/light themes

Filter by genre (with live updates)

Built with HTML, Bootstrap, and vanilla JavaScript, this project showcases core front-end development skills, clean UI/UX, and interactive user features.

🧠 Project Approach
1. 🎯 Objective Definition
Build a user-friendly movie explorer.

Ensure responsive design for mobile & desktop.

Provide persistent watchlist without backend using localStorage.

2. ⚙️ Technology Stack
Frontend: HTML, Bootstrap 5, Vanilla JavaScript

API: OMDb API

Persistence: localStorage for storing watchlist

Icons/UI: Bootstrap Icons

3. 🏗️ Component-Based Breakdown
Navbar: Branding, navigation links, theme toggle

Search Bar: Debounced input with live search and back-to-home button

Movie Grid: Dynamically renders movie cards (with poster, year, add button)

Watchlist Panel: Displays added movies, allows deletion

Toast Alerts: Displays feedback (e.g., added, removed, duplicate)

4. 🌗 Theme Switching
Implemented dark/light toggle using class switching and localStorage to remember the theme.

5. 🧪 Testing & Debugging
Handled edge cases like:

No results from API

Duplicate entries in watchlist

Invalid poster URLs

Ensured UI does not break in mobile views.

6. 📦 Final Touches
Genre-based filtering (with dropdown and filter logic)

Back button shown on search to return to home layout

Toast alerts for feedback

Sticky watchlist with scrollable container

