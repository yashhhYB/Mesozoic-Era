# 🦕 Mesozoic Era – Explore the World of Dinosaurs

Welcome to **Mesozoic Era**, an immersive, interactive platform to explore dinosaurs in 3D space — powered by **Google Maps Platform** and **CesiumJS**.

> 🏆 Built for educational exploration, scientific curiosity, and geographic storytelling.

---

## 🔗 Live Demo

👉 [Try the App](https://mesozoic-era0.netlify.app/)

🎥 [Watch Demo Video](https://www.youtube.com/watch?v=vyNAfmxPHlw)

---

## 🚀 Project Overview

**Mesozoic Era** is an interactive web app that brings the prehistoric world to life. Using a combination of **Cesium's 3D globe rendering** and **Google Maps geolocation tools**, users can explore iconic dinosaurs, view fossils near their region, and even simulate battles between creatures from different periods.

This project highlights how **Google Maps Platform** can be used not just for navigation, but for rich, immersive educational applications.

---

## ✨ Key Features

### 🌍 3D Globe Visualization
- Uses **CesiumJS** + Google Photorealistic 3D Tiles
- Interactive Earth with zoom and sky atmosphere
- Click to focus on fossil regions or countries

### 🦖 Dinosaur Explorer
- View details about 13+ dinosaurs from the Triassic, Jurassic, and Cretaceous periods
- Responsive card grid with filters for:
  - Era (Jurassic, Triassic, Cretaceous)
  - Diet (Carnivore, Herbivore, Omnivore)
  - Size & Speed

### 🔬 Detailed Dino Profiles
- Carousel of high-resolution images
- Timeline, habitat info, brain size, fossil sites, fun facts
- Compare dinosaur size vs humans visually
- Scrollable, tabbed, responsive layout

### 📍 Dinosaurs Near You
- Uses **Google Geolocation API**
- Detects your location and shows nearby fossil discoveries
- Option to search manually by city or coordinates
- View as map or card grid

### ⚔️ Dinosaur Fights
- Battle simulator where users choose two dinosaurs
- Displays stats like bite force, speed, intelligence
- Simulates a battle with fun animation and logic
- Random winner or skill-based prediction system

### 🌙 Dark Mode + Mobile Friendly
- Toggle between light and dark themes
- Fully responsive and designed for mobile-first experience

### 🧠 Daily Dino Fact
- Fun new fact every day pulled from curated list
- Shows in header or footer area with smooth animation

---

## 🛠 Tech Stack

| Frontend        | Mapping & 3D       | Styling & UI         |
|-----------------|--------------------|-----------------------|
| React + Next.js | CesiumJS           | Tailwind CSS          |
| TypeScript      | Google Maps API    | ShadCN UI + Framer Motion |

---

## 📍 Google Maps Platform Usage

- **Geocoding API**: Convert user geolocation to place name for “Dino Near You”
- **Maps JavaScript API**: Used in fossil location view
- **Cesium + Google 3D Tiles**: Renders full Earth with photorealistic terrain

> This project goes beyond navigation, demonstrating Google Maps Platform in a **scientific, educational storytelling context**.

---

## 📁 How to Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/yashhhYB/Mesozoic-Era.git
cd Mesozoic-Era
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your-google-api-key
NEXT_PUBLIC_CESIUM_ACCESS_TOKEN=your-cesium-access-token
```

### 4. Run the App

```bash
npm run dev
```

> The app runs locally at `http://localhost:3000`

---

## 💡 Inspiration

The idea for **Mesozoic Era** came from combining our love for Google Earth, ancient creatures, and the power of educational storytelling through immersive design. What if Jurassic Park had a digital twin you could explore?

This project blends **maps**, **science**, and **fun** — and pushes the limits of browser-based 3D learning.

---

## 🙋‍♂️ Created By

**Yash Bodade**
[LinkedIn](https://linkedin.com/in/yashbodade) • [GitHub](https://github.com/yashhhYB) • [Portfolio](https://yashbodade.vercel.app)

---

## ⭐️ Support

If you like this project, please give it a ⭐ on GitHub — it motivates me to build more cool stuff!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

```


I'll be happy to help tailor it further!
```
