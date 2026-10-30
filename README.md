# 🚌 DNR College Bus Tracker

A real-time bus tracking and route management web application built for students, drivers, and management of **DNR College of Engineering & Technology (Bhimavaram)**.

Live Demo: [https://projectlabdnr-creator.github.io/DNR-bus-tracker/](https://projectlabdnr-creator.github.io/DNR-bus-tracker/)

---

## 📌 Overview

The **DNR College Bus Tracker** bridges the communication gap between transit drivers, students, and administration. It provides real-time GPS tracking, estimated arrival times, route-specific administrative notices, and an instant emergency alert system to keep daily commutes safe, transparent, and predictable.

---

## ✨ Features by Portal

### 🎓 1. Student Portal
* **Live GPS Tracking:** Follow the assigned bus in real-time on an interactive map.
* **Route Insights:** View current speed, GPS signal health, live distance to college, and calculated ETA.
* **Announcements Feed:** Receive instant route-specific or campus-wide alerts and timetable updates.
* **Emergency Broadcast Listener:** Immediate visual banner and siren alert during critical transit incidents.

### 🚌 2. Driver Portal
* **One-Tap Location Sharing:** Share high-accuracy live GPS telemetry with active students while running the route.
* **Screen Keep-Awake:** Prevents mobile display sleep during continuous transit tracking.
* **Telemetry Diagnostics:** Real-time visibility into GPS accuracy, broadcast latency, and transmission status.
* **Emergency Siren & Dispatch:** Instant alert dispatcher for accidents, breakdowns, or medical emergencies with siren triggers sent to route members.

### ⚙️ 3. Management Portal
* **Password-Protected Administration:** Secure access panel for college transit coordinators.
* **Fleet Overview:** Monitor all active buses, driver connectivity, and routes across Bhimavaram and neighboring regions.
* **Bus Registration & Updating:** Register new bus IDs (e.g., `BUS-01`, `BUS-02`) or update assigned route paths.
* **Broadcast Announcements:** Dispatch immediate route-targeted or campus-wide broadcast messages with audible chime notifications.

---

## 🗺️ Supported Sample Routes

* **BUS-01:** Bhyravapatnam ➔ DNR College of Engineering & Technology
* **BUS-02:** Ganapavaram ➔ DNR College of Engineering & Technology
* **BUS-03:** Palakollu ➔ DNR College of Engineering & Technology

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Mobile-first responsive design), JavaScript (ES6+)
* **Mapping & Telemetry:** Geolocation API, Web Mapping Libraries (Leaflet / OpenStreetMap)
* **Real-time Backend / Database:** Firebase Realtime Database / Supabase / WebSockets
* **Hosting:** GitHub Pages

---

## 🚀 Getting Started

### Prerequisites

* Modern web browser (Chrome, Safari, Firefox, Edge) with Geolocation permissions enabled.
* A local static server or GitHub Pages for deployment.

### Local Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/projectlabdnr-creator/DNR-bus-tracker.git](https://github.com/projectlabdnr-creator/DNR-bus-tracker.git)
   cd DNR-bus-tracker
   
