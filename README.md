<img width="1355" height="643" alt="image" src="https://github.com/user-attachments/assets/930cd357-daba-4d10-bfc7-327ddf88ed21" /># 📡 MQTT Dashboard Starter Kit (UI Only)

A modern, interactive **MQTT Dashboard Starter Kit** built with **HTML, CSS, and JavaScript (UI only)**.\
This project simulates the look and feel of a real IoT dashboard where users can connect to MQTT brokers, publish/subscribe to topics, and view real-time data streams.

Currently, only the **UI components** are implemented — backend logic and real MQTT/AWS IoT Core integration are coming next.

---

## ✨ Features (UI Simulation Only)

### 🔌 Broker Connection

- Connect modal for entering broker details (MQTT / AWS IoT Core)
- Animated **Connecting…** → ✅ Connected / ❌ Failed status
- Footer shows live connection status

### 📤 Publishing Messages

- Input for topic name
- JSON payload editor
- Publish button (sends message to logs + charts simulation)

### 📥 Subscribing to Topics

- Add multiple subscriptions (e.g., `home/livingroom/temp`)
- Active subscriptions list in sidebar
- Incoming messages appear in **logs + charts**

### 📊 Real-Time Charts & Logs

- Simulated IoT data streams (temperature, humidity, voltage)
- Real-time updating charts (line/area)
- Logs panel with timestamp + color-coded JSON payloads

### 🤖 AI Insights (Simulated)

- Example analytics & suggestions:
  - “Average temperature in last 5 mins: 28.4°C”
  - “Device X is publishing too frequently”
  - “Broker load is stable for 500 devices”

### ⚡ Broker Performance Card

- Toggle between 100 / 500 / 1000 simulated devices
- Fake stats: messages per second, CPU/memory usage
- Alerts if usage > 80%

### ☁️ AWS IoT Core Simulation (UI)

- Thing Registry (mock Things online/offline)
- Device Shadows viewer (`desired`, `reported`, `delta`)
- IoT Rules simulation with triggers
- Cloud metrics (latency, msg/sec, connected Things)
- AI-style AWS insights

### 🎨 UI/UX Highlights

- Professional SaaS dashboard look
- Dark/light theme toggle
- Smooth animations (connecting spinner, chart updates)
- Responsive grid layout (desktop + mobile)
- Primary Colors:
  - Blue `#2563EB` → Primary
  - Green `#10B981` → Success
  - Red `#EF4444` → Alerts

---

## 🚧 Project Roadmap

✅ **Phase 1 (Current)** – UI Components

- Dashboard layout, modals, cards, charts, and logs simulation

🔜 **Phase 2** – MQTT Broker Integration

- Connect to public brokers (e.g., HiveMQ, Eclipse Mosquitto)
- Handle real publish/subscribe messages

🔜 **Phase 3** – AWS IoT Core Integration

- Support for IoT Thing registry, Shadows, and Rules engine
- Display AWS IoT metrics

🔜 **Phase 4** – AI Insights with Real Data

- Implement basic analytics and suggestions using real data streams

---

## 🛠️ Tech Stack

- **HTML5** – Structure
- **CSS3 (Flex/Grid)** – Styling
- **Vanilla JavaScript (ES6+)** – UI interactivity
- **Chart.js / D3.js (planned)** – Charts & real-time visualization

---

## 🚀 Getting Started

Clone the repo:

```bash
https://github.com/bitcrawllers/mqtt-dashboard-starter-kit
cd mqtt-dashboard-starter-kit
```

Open `index.html` in your browser — no build required.

---

## 📸 Screenshots (UI Preview)

<img width="1355" height="643" alt="image" src="https://github.com/user-attachments/assets/f8a5ac65-166d-473b-9ff1-7c04218e189f" />


---

## 🤝 Contributing

Pull requests are welcome!\
For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

MIT License © 2025 [Your Name / BitCrawllers]

