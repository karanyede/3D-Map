# 🌍 Photorealistic 3D Map using Google Maps JavaScript API

This project is a hands-on implementation from the [Google Developers Codelab](https://developers.google.com/codelabs/maps-platform/maps-platform-101-3d-maps-js), where a photorealistic 3D map is created and customized using the Maps JavaScript API.

## 📌 Features

- Load the Maps JavaScript API dynamically  
- Display a 3D map centered on the CN Tower, Toronto  
- Draw and extrude polygons to highlight specific areas  
- Customize visible map features (e.g., hiding points of interest)

## 🛠️ Technologies Used

- HTML5
- JavaScript (ES6)
- Google Maps JavaScript API

## 📂 Folder Structure

```
project-root/
├── index.html
├── script.js
├── style.css (optional)
├── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/photorealistic-3d-map.git
cd photorealistic-3d-map
```

### 2. Add Your Google Maps API Key

Replace `"YOUR_API_KEY"` in `index.html` with your actual Google Maps API key.

```html
<script async
  src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
</script>
```

### 3. Open the Project

Simply open `index.html` in your browser to view the map.
