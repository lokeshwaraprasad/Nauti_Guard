# Nauti_Guard
An repo consisting of code for developing an app for ramweshwaram fisher to detect the international sea boundary
# 🐟 Rameshwaram Fisherman Alert System 🚨🌊

A **life-saving, real-time IoT solution** built to **alert Indian fishermen near Rameshwaram** before crossing the **50 nautical miles boundary** of Sri Lanka. This project leverages **LoRa, LiDAR**, and other smart technologies to **track boats**, **analyze positions**, and **warn crews ahead of danger**.

---

## 📌 Objective

To **prevent accidental border crossings** into Sri Lankan waters by:
- **Tracking fishermen’s boats in real-time**
- **Alerting them before reaching the international maritime boundary**
- **Improving safety, awareness, and response with modern tech**

---

## 🚀 Key Features

| Feature                          | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| 🌐 Real-Time Location Tracking   | Uses GPS + LoRa mesh network to monitor boats even in low-signal zones     |
| 📡 Boundary Alert System         | Sends alerts as boats approach **50 nautical miles** from Sri Lanka        |
| 🔦 LiDAR Obstacle Detection      | Avoids collisions and detects nearby vessels in fog or darkness            |
| 📲 Fisherman-Friendly App        | Simple UI showing safe zones, alert levels, and help options               |
| 📍 Geo-Fencing & Offline Maps    | Pre-loaded maritime boundaries with alerts even when offline               |
| 🔔 Multi-Channel Alerting        | Buzzer, light signal, and mobile push notifications                        |
| 🌐 Cloud Sync & Dashboard        | Centralized control room dashboard to monitor fleet and respond quickly    |
| 🧠 AI Route Suggestions          | Suggests optimal routes based on weather and safety data                   |

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (PWA enabled)
- **Backend:** Node.js, Express.js
- **IoT Hardware:** Arduino / ESP32, GPS Module, LoRa Module, LiDAR Sensor
- **Data Storage:** Firebase / JSON mock data (for demo)
- **Maps & Navigation:** Leaflet.js, OpenSeaMap, GeoJSON
- **Communication:** LoRa Mesh, GSM fallback
- **Dashboard:** Realtime updates with WebSocket / MQTT

---

## 📱 Mobile App Features

- 📍 Current location with proximity alert
- 🧭 Boundary distance countdown
- 🆘 Emergency SOS button with last known location
- 📷 Optional integration with camera for live sharing

---

## 💡 How It Works

1. **Boat is equipped with a GPS + LoRa device**
2. Real-time location sent to control room and app
3. If boat is within **50 NM** of international boundary:
    - 🔔 Alert triggered (sound + light + push notification)
    - Route correction advice shown
4. **Control room** can take over monitoring if the boat is unresponsive

---

## 🌐 System Architecture

