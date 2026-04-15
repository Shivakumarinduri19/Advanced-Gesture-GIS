# Digi-Hand GIS: The Digitalization of Motion 🌍🖐️

**Digi-Hand GIS** is an innovative, browser-based Geospatial Information System (GIS) that translates physical hand movements into high-precision digital commands. By leveraging Computer Vision (AI) to digitalize skeletal hand landmarks, this project eliminates the need for traditional input devices, offering a touchless, intuitive way to interact with global spatial data.

---

## 🚀 Live Experience
[**Launch the Live Demo**](INSERT_YOUR_GITHUB_PAGES_LINK_HERE)

---

## 🛠️ Key Innovations & Features

### 1. Motion Digitalization
Unlike traditional mouse-based navigation, Digi-Hand GIS uses a **MediaPipe-powered AI pipeline** to track 21 skeletal hand landmarks in real-time. These landmarks are mapped to a coordinate system, digitalizing human gestures into actionable GIS data.

### 2. X-Ray Spectral Lens
A dynamic "Flashlight" effect that allows users to hover over a vector map to reveal high-resolution **Satellite Imagery** within a localized radius. This allows for rapid cross-referencing of infrastructure without visual clutter.

### 3. Precision Drawing Engine
* **Point, Line, & Polygon:** Intelligently detects gesture sequences to create complex geometries.
* **Proximity Snapping:** Automatically closes polygons when the cursor returns to the origin node.

### 4. Real-Time Spatial Analytics
* **Digital Tape Measure:** An anchored "rubber-band" measurement tool that calculates geodesic distances in real-time as the user moves their hand.
* **Smooth Logarithmic Zoom:** A refined scaling algorithm that adjusts map depth based on the physical spread between the index and middle fingers.

### 5. Gesture-Based Data Management
* **Fist-to-Clear:** A deliberate, 1-second "Fist" gesture serves as a high-reliability command to wipe all temporary spatial data from the session, preventing accidental data loss.

---

## 📖 Gesture Legend

| Gesture | Mode | Action Description |
| :--- | :--- | :--- |
| ✋ **Relaxed Palm** | **Measure** | Navigate and view live distance from the last node. |
| 🤏 **Pinch** | **Draw** | Drop a point node. Connects lines/polygons automatically. |
| ✌️ **Spread** | **Zoom** | Change distance between index/middle fingers to zoom. |
| ✊ **Closed Fist** | **Clear** | Hold for 1 second to wipe all drawn data from the map. |

---

## 💻 Tech Stack

* **Mapping Engine:** [Leaflet.js](https://leafletjs.com/)
* **Computer Vision:** [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
* **UI/UX:** HTML5 (Canvas Overlay), CSS3 (Glassmorphism), JavaScript (ES6+)
* **Base Maps:** CartoDB Dark Matter & ESRI World Imagery

---

## 🔧 Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/your-repo-name.git](https://github.com/YOUR_USERNAME/your-repo-name.git)
