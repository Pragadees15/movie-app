# Movie App

A simple movie application that fetches and displays popular movies using The Movie Database (TMDB) API. Users can also search for movies using the search bar.

## Features
- Fetches and displays popular movies from TMDB API
- Displays movie posters, titles, ratings, and an overview
- Color-coded ratings for easy visualization:
  - Green (8 and above)
  - Orange (5 to 7.9)
  - Red (Below 5)
- Search functionality to find specific movies
- Responsive design with a modern UI

## Technologies Used
- HTML
- CSS
- JavaScript (ES6+)
- TMDB API

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Pragadees15/movie-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-app
   ```
3. Open `index.html` in your browser.

## API Configuration
This project uses **The Movie Database (TMDB) API**. You need an API key to run the project.

1. Get your API key from [TMDB](https://www.themoviedb.org/documentation/api)
2. Replace the placeholder API key in `script.js`:
   ```javascript
   const API_KEY = 'your_api_key_here';
   ```

## File Structure
```
movie-app/
│── index.html       # Main HTML file
│── style.css        # Styling for the app
│── script.js        # JavaScript logic
└── README.md        # Project documentation

Happy Coding! 🎬🍿
