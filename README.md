## Mini Movie Explorer – Project Overview & Approach

### Overview
Mini Movie Explorer is a responsive, single-page web application that allows users to:
- Search movies using the OMDb API
- Add/remove movies to a personalized watchlist (stored in localStorage)
- Toggle between dark/light themes
- Filter by genre with live updates

Built using HTML, Bootstrap, and vanilla JavaScript, the project demonstrates clean UI/UX and interactive user features without the need for a backend.

---

### Project Approach

#### 1. Objective
- Build a user-friendly movie discovery interface.
- Ensure the application is fully responsive and accessible.
- Maintain watchlist data persistently using browser localStorage.

#### 2. Technology Stack
- **Frontend:** HTML5, Bootstrap 5, JavaScript
- **API:** OMDb API for movie search and metadata
- **Storage:** localStorage for persistent watchlist data
- **Icons:** Bootstrap Icons

#### 3. Functional Modules
- **Navbar:** Contains branding, navigation links, and theme toggle button.
- **Search Bar:** Includes live search with debounce and a "Back" button for navigation control.
- **Movie Grid:** Dynamically renders movie cards with posters, titles, and "Add to Watchlist" buttons.
- **Watchlist Panel:** Displays saved movies, allowing users to remove entries.
- **Toast Notifications:** Provides feedback when adding or removing movies, or handling duplicates.

#### 4. Theme Handling
- Theme toggle implemented with a light/dark mode switch.
- User preference saved in localStorage for persistent experience across sessions.

#### 5. Logic and User Experience
- Used debounced search to avoid excessive API calls.
- Displayed placeholder images if no movie poster is available.
- Prevented duplicate entries in watchlist.
- Maintained a responsive, centered layout using Bootstrap grid system.

---
#### 6. Images

<img src="https://github.com/ichhakumari/Mini-Movie-Explorer/blob/main/output1.png">
<hr>
View movie discription:
<img src= "https://github.com/ichhakumari/Mini-Movie-Explorer/blob/main/Screenshot%202025-07-09%20151803.png">

<hr>
Search movies:
<img src ="https://github.com/ichhakumari/Mini-Movie-Explorer/blob/main/output2.png">
<hr>

Remove from watchlist:

<img src = "https://github.com/ichhakumari/Mini-Movie-Explorer/blob/main/output3.png">
<hr>

Added to watchlist:
<img src= "https://github.com/ichhakumari/Mini-Movie-Explorer/blob/main/putput4.png">

---
THANK YOU :)
