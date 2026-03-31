# Neon Hill Climb

A physics-driven, web-native 2D hill climbing game featuring procedural terrain, custom audio synthesis, an integrated upgrade economy, and a real-time global leaderboard. 

## 🚀 Features

* **Custom 2D Physics:** Implements particle-based integration and kinematic constraints for realistic suspension and tire friction.
* **Dynamic Terrain Generation:** Procedurally generated sine-wave terrain that progressively increases in difficulty the further you drive.
* **Garage & Progression System:** A fully functional economy allowing players to collect coins and upgrade Engine, Fuel Capacity, and Tires. User progress persists via browser `localStorage`.
* **Global Leaderboard:** Integrated with Firebase Realtime Database (RTDB) to track and display the top 10 highest distances globally.
* **Procedural Audio:** Utilizes the Web Audio API for dynamic engine roaring, low-pass filtering, and sound effects—without relying on external audio assets.
* **Cross-Platform Controls:** Supports both keyboard inputs (PC) and interactive on-screen UI buttons (Mobile/Tablet).

## 🛠️ Tech Stack

* **Frontend:** HTML5 Canvas, CSS3, Vanilla JavaScript (ES6+)
* **Backend / Database:** Firebase Realtime Database
* **Audio:** Web Audio API
