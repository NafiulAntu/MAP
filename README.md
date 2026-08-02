# Mapty // Map Your Workouts

Mapty is a web application that allows users to track and log their running and cycling workouts on an interactive map using geolocation.

---

## 🚀 Features

* **Geolocation Integration**: Automatically detects the user's current location on map load using the Browser Geolocation API.
* **Interactive Map**: Built with the Leaflet.js library using OpenStreetMap tiles to render pins and popups.
* **Workout Types**:
  * **Running**: Track distance, duration, cadence (steps/min), and calculated pace (min/km).
  * **Cycling**: Track distance, duration, elevation gain (meters), and calculated speed (km/h).
* **Map Navigation**: Clicking on a logged workout in the list smoothly pans the map view directly to that workout's location marker.
* **Local Storage Persistence**: Workouts are saved in the browser's `localStorage` so data remains available across page reloads.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3**: Modern layouts using Flexbox, CSS Grid, and custom variables.
* **JavaScript (ES6+)**: Object-Oriented Programming (OOP) design using classes, inheritance, private class fields (`#map`, `#workouts`), and event handling.
* **Leaflet.js**: Lightweight open-source JavaScript library for interactive maps.
* **Google Fonts**: Custom typography using *Manrope*.

---

## 📂 Project Structure

```text
├── index.html                    # Main HTML markup
├── style.css                     # Custom styling & dynamic state classes
├── script.js                    # Core application logic & OOP classes
├── icon.png                      # Favicon / Map pin icon
├── logo.png                      # App brand logo
├── Mapty-architecture-final.jpg  # Complete OOP architecture diagram
├── Mapty-architecture-part-1.jpg # Base OOP architecture diagram
└── Mapty-flowchart.jpg           # Application execution flowchart
