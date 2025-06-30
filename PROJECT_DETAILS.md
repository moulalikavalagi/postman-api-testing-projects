# 🚀 Postman API Testing Projects

Real-time API testing projects built with Postman — no mock servers, just real request/response workflows using `https://httpbin.org`.

---

## 🛩 Project 1: Drone Delivery Tracker

Simulates a drone fleet updating location and completing deliveries.

### 🔧 Features:
- `POST /drones/:id/update`: Updates drone location
- `PUT /drones/:id/update-details`: Updates config like battery, speed
- Pre-request scripts to randomize GPS and timestamps
- Test scripts for:
  - Geo bounding (lat/lng)
  - Status code validation
  - Drone ID checks

---

## 🌫 Project 2: UrbanAirX – Air Quality Monitoring API

Simulates AQI sensors reporting air quality in different zones.

### 🔧 Features:
- `POST /sensors/:id/data`: Submits AQI and PM2.5 readings
- `PUT /sensors/:id/config`: Updates sensor zone, sampling rate
- `POST /alerts/send`: Manually trigger alert
- Test scripts for:
  - AQI range validation
  - Sensor data completeness
  - Alert structure

---

## ✅ Postman Concepts Used:
- Raw Body JSON (POST, PUT)
- Pre-request scripts (`pm.variables.set`, dynamic payloads)
- Test scripts (`pm.test`, `pm.expect`)
- Environment variables
- CSV data-driven Collection Runner (optional)

---

## 📂 How to Run:
1. Open Postman → Click `Import`
2. Upload `.postman_collection.json` files
3. Select the desired request (PUT, POST)
4. Go to `Body → raw → JSON`, paste example data
5. Click `Send` and check `Tests` tab for validation

---

## 🧠 Skills Demonstrated:
- Real-world API request flow simulation
- Writing test automation logic in Postman
- Mastery of multiple HTTP methods
- Structuring clean, modular Postman collections

---

## 📎 Author
**[MOULALI KAVALAGI]**  

