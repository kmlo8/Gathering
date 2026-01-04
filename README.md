# Gathering
# 🌍 MapChat / Gathering

**Connect with your local community in real-time.**

This project is a full-stack social platform that combines real-time geolocation with community building. Unlike standard social networks, it focuses on **in-person connections** facilitated by a "Trust Score" reputation system. Users can explore a live map to find nearby events, join "Tribes" (interest groups), and chat instantly with neighbors—all while maintaining privacy and safety.

## 🚀 Key Features

* **📍 Live Map Discovery:** Visualize users, events, and tribes nearby in real-time using Mapbox & PostGIS.
* **🛡️ Reputation System:** A "Trust Score" (0-100) for every user based on successful meetups and peer vouches.
* **⚡ Real-Time Chat:** Instant messaging powered by Socket.IO for 1-on-1 and event-based group chats.
* **💎 Glassmorphism UI:** A modern, dark-mode aesthetic built with Tailwind CSS v4 and Framer Motion.
* **tribe-based Communities:** Join local groups like "Night Runners" or "Vegan Chefs."

## 🛠 Tech Stack

**Frontend:**
* React 18 + TypeScript + Vite 5
* Tailwind CSS v4 (Glassmorphism)
* Zustand (State) + TanStack Query
* Framer Motion (Animations)

**Backend:**
* NestJS 10 (Node.js)
* PostgreSQL + PostGIS (Spatial Data)
* Socket.IO (Real-time Gateway)
* Redis (Caching & Throttling)
* Docker Compose (Infrastructure)
