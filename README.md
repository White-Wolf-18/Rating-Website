# 🎬 Rating Hub

A sleek, responsive personal scoreboard for tracking and rating Movies, Anime, and TV Series. This project serves as a digital viewing diary, built with a focus on clean UI and dynamic content filtering.

## 🌟 Features

* **Dynamic Data Loading**: Uses asynchronous JavaScript (`fetch`) to load content from local JSON files (`movies_data.json`, `anime_data.json`, `series_data.json`).
* **Real-time Filtering**: 
    * Search by title with live results.
    * Filter Movies by release year.
    * Filter Anime and Series by status (Ongoing/Completed).
* **Auto-Sorting**: High-rated titles are automatically prioritized at the top of the list.
* **Responsive Design**: Built with **Bootstrap 5.3**, ensuring a premium experience on mobile, tablet, and desktop.
* **Custom UI**: Features a custom dark-themed CSS with glassmorphism-inspired hover effects and gold accents.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3 (Custom Variables), Bootstrap 5.3.
* **Logic**: Vanilla JavaScript (Async/Await, DOM Manipulation).
* **Data Storage**: JSON-based flat files.

## 📂 Project Structure

```text
Movie-Rating-Website/
├── json_files/
│   ├── movies_data.json   # Movie database
│   ├── anime_data.json    # Anime database
│   └── series_data.json   # TV Series database
├── index.html             # Movie scoreboard (Home)
├── anime.html             # Anime scoreboard
├── series.html            # TV Series scoreboard
├── about.html             # Rating philosophy & info
├── style.css              # Custom styling and animations
├── logo.png               # Brand identity
└── background.jpg         # Global site background
```
## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/White-Wolf-18/Movie-Rating-Website.git](https://github.com/White-Wolf-18/Movie-Rating-Website.git)
   ```
2. **Setup your data: Ensure your JSON files (e.g., movies_data.json) are structured as follows in the json_files/ folder**:
   ```bash
    {
      "title": "Example Title",
      "description": "Short description here...",
      "rating": 9.5,
      "image_src": "link-to-poster.jpg",
      "year": 2024,
      "status": "Completed",
      "episodes": 10
   }
    ```
Run the site: Simply open index.html in your browser.

Note: Since the project uses the JavaScript Fetch API to load JSON data, you may need to use a local server (like the VS Code Live Server extension) to avoid CORS browser security errors.

## 📋 Rating Philosophy
As detailed in the about.html page:

10/10: A personal favorite; a must-watch experience.

8-9/10: Excellent entertainment and highly recommended.

5-7/10: Solid but flawed; good for a casual watch.

1-5/10: Very bad; Not worth your time.

## 🤝 Contributing
This is a personal hobby project, but feel free to fork the repository and customize it for your own watchlists!
