# 🗺️ Travel Companion Route Planner

Personalized travel route planner recommending curated Indian destinations based on your companion group (Friends, Family, Solo). Features a secure login gateway, dynamic category selector, and a full-screen Mapbox navigation interface with live geolocation, destination search, and real-time turn-by-turn driving directions.

---

## 🚀 Key Features

* **👥 Companion-Based Curation:** Curated travel recommendations tailored to your traveling group:
  * **Family:** Cultural and spiritual landmarks like Kashi, Vaishno Devi, Bhadrachalam, Kashmir, and Kanyakumari.
  * **Friends:** Adventure and scenic hotspots like Leh-Ladakh, Kerala, Vizag, Manali, and Kashmir.
  * **Common/Solo:** Popular all-round getaways like Jaipur, Rishikesh, Andaman & Nicobar, Ooty, Munnar, and Isha Foundation (Coimbatore).
* **🗺️ Interactive Map Interface:** A fully responsive full-screen map interface modeled after leading navigation platforms.
* **📍 Real-Time Navigation & Routing:** Seamless integration with Mapbox Directions for calculating optimal routes, turn-by-turn navigation instructions, and travel times.
* **📱 Geolocation Aware:** Automatically prompts for location access to center the map on the user's current location and provide local routing.
* **🔐 Secure Entry Flow:** A clean, multi-step portal experience (Secure Login ➔ Dynamic Category Selection ➔ Interactive Map Directions).

---

## 🛠️ Tech Stack

* **Frontend Structure:** HTML5
* **Styling & Presentation:** CSS3 (Vanilla, custom background elements)
* **Logic & Interactions:** JavaScript (ES6)
* **Map Services & GIS:** 
  * [Mapbox GL JS v1.12.0](https://docs.mapbox.com/mapbox-gl-js/api/) (High-performance vector map rendering)
  * [Mapbox GL Directions v4.1.0](https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-directions/) (Route navigation and step-by-step instructions)

---

## 📂 Project Structure

```bash
website234/
├── 🌐 index.html          # Map rendering & Mapbox Directions page
├── 🌐 main.html           # Secure portal login entry page
├── 🌐 options.html        # Dynamic travel category selector
├── 📜 script.js           # Mapbox integration, GPS locating & route calculation
├── 📁 media/              # Visual assets & icons
│   └── header-1.png
├── 🖼️ pexels-sbsoneji...jpg # Background images for premium visual framing
├── 🖼️ palace-7421313...jpg  # Background images for premium visual framing
├── 📄 .hintrc             # Code style & hint configurations
└── 📝 README.md           # Documentation
```

---

## 💻 Running Locally

Since this application utilizes Mapbox GIS components and Geolocation APIs, it requires a secure local context or local server to run correctly.

### Option 1: Using Python (Simplest)
If you have Python installed, navigate to the project directory and run:
```bash
python -m http.server 8000
```
Then, open your browser and navigate to **`http://localhost:8000/main.html`**.

### Option 2: Using Node.js / NPM
If you prefer Node.js, run:
```bash
npx http-server -p 8000
```
Then, open your browser and navigate to **`http://localhost:8000/main.html`**.

---

## 🌟 Future Enhancements

* **💎 Glassmorphic UI Redesign:** Upgrading to a ultra-modern CSS layout with premium blurred backdrops, glowing gradients, and custom dark/light modes.
* **🗄️ Database Integration:** Incorporating a backend database (e.g., Firebase, Supabase) for user accounts and saving favorite travel routes.
* **🗺️ Automatic Waypoints:** Allowing users to click directly on a curated destination and automatically plot a route from their live location with a single click.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
