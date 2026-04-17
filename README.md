# 🗺️ Realtime Location Tracker

A real-time device tracking application built with Node.js, Express, Socket.io, and Leaflet Maps. Track multiple users' locations in real-time with room-based sessions.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

## ✨ Features

- 🔴 **Real-time GPS tracking** - Live location updates using geolocation API
- 🚪 **Room-based sessions** - Create and join specific tracking rooms
- 👥 **Multi-user support** - Track multiple devices simultaneously
- 🗺️ **Interactive maps** - Powered by Leaflet and OpenStreetMap
- 🎨 **User identification** - Custom names and color-coded markers
- 📱 **Responsive design** - Works on desktop and mobile devices
- ⚡ **WebSocket communication** - Instant updates via Socket.io

## 🚀 Demo

### Quick Start
```bash
# Using room parameter
http://localhost:3000?room=room1&name=Alice

# Share with others
http://localhost:3000?room=room1&name=Bob
