# 🗺️ Path Finder

## 🧭 Shortest Route Finder (Single-page HTML)

A lightweight, interactive web app for finding shortest routes between points using:

- 📍 Browser Geolocation  
- 🗺️ OpenStreetMap + Leaflet  
- 🔎 Nominatim Geocoding  
- 🚗 OSRM Routing  

Perfect for learning map APIs, UX design, and route visualization.

---

## ✨ Features

- Detect current user location
- Reverse geocoding (coordinates → address)
- Use current location as origin
- Manual input support
- Sample cities (New York, London, Tokyo, Sydney)
- Multiple travel modes:
  - 🚗 Driving
  - 🚴 Cycling
  - 🚶 Walking / Hiking
- Route visualization (map + polyline + markers)
- Route summary:
  - Distance
  - Time
  - ETA
  - Speed
- Turn-by-turn directions with icons
- Collapsible UI panels
- Clean Tailwind UI with loading & error states

---

## 🧩 Tech Stack

- HTML5 + CSS + Vanilla JS  
- Tailwind CSS (CDN)  
- Leaflet.js  
- OpenStreetMap Tiles (Carto Voyager)  
- Nominatim API  
- OSRM API  

⚡ No build tools required — single file project

---

## 🚀 Getting Started

### ▶️ Run Locally

1. Open `activity.html` in browser  
2. Allow location permission (or use sample location)  
3. Enter origin + destination  
4. Select travel mode  
5. Click **Find Shortest Path**

---

## ⚙️ Requirements

- Internet connection (for APIs)
- Modern browser
- HTTPS recommended (for geolocation)

---

## 🎯 App Features Breakdown

### 📍 Geolocation
- Get current location
- Permission handling UI
- Fallback to manual/sample input

### 🧾 Route Form
- Origin + Destination input
- Travel modes:
  - driving-car, driving-hgv  
  - cycling-regular, cycling-road, cycling-mountain, cycling-electric  
  - foot-walking, foot-hiking  

### 🗺️ Map
- Leaflet integration
- Route polyline + markers
- Auto-fit bounds

### 📊 Route Details
- Distance, time, ETA
- Avg speed
- Step count, turns, segments
- Visual route bars
- Expandable directions panel

### 🎨 UI
- Loading indicators
- Error messages
- Icons & animations

---

## 📁 Code Structure
activity.html
│
├── <head>
│ ├── Tailwind CDN
│ ├── Leaflet CSS
│ └── Custom styles
│
├── <body>
│ ├── Header
│ ├── Geolocation section
│ ├── Route form
│ ├── Map (#map)
│ ├── Route details (#route-details)
│ ├── Directions panel (#directions-panel)
│ └── Footer
│
└── <script>
├── Map initialization
├── Geolocation handling
├── Geocoding functions
├── Routing (OSRM)
├── UI updates


---

## 🔧 Customization

- Update contact/social links in footer
- Modify travel modes (`<select id="travel-mode">`)
- Change map tile provider
- Customize styles (colors, animations)
- Add new sample cities
- Extend OSRM profiles

---

## 🧪 Use as Template

- Copy `activity.html`
- Run with:
  - Live Server (VS Code)
  - Python server (`python -m http.server`)
- Extend features:
  - Autocomplete search
  - Offline caching
  - Distance unit toggle (km/miles)

---

## 📝 Notes

- Geolocation may fail if permission denied
- OSRM API → avoid excessive requests
- Nominatim → rate-limited (use responsibly)
- Works best on HTTPS

---

## 📬 Author

**Abhishek Kumar**

- 📧 Email: kabhishek10266@gmail.com  
- 💻 GitHub: https://github.com/Kabhi001  
- 🔗 LinkedIn: https://www.linkedin.com/in/abhishek266/  
- 📸 Instagram: https://www.instagram.com/a6hishek_27.6/

---

> ✨ *Simple map app with detailed route insights*
