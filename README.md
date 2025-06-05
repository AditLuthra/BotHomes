# 🏠 BotHomes – The Smart Home OS by Botness

> **Local-first. Maker-powered. Cloud-optional.**  
> Built by [Botness Technologies](https://github.com/AditLuthra), BotHomes is a privacy-respecting, modular, and fully hackable smart home OS that runs at the edge — because real automation doesn’t need the internet.

---

## 🚀 What Is BotHomes?

BotHomes is a custom smart home ecosystem designed for makers, engineers, and rebels who want full control of their living space — without relying on big-tech clouds.

Built around **ESP32** devices and a **self-hosted dashboard**, it lets you control everything from lights to security, your way.

---

## 🎯 Core Features

- 🌐 **Local-first control** – Works without internet
- 🔧 **Modular ESP32 firmware** – Add nodes as you go
- 📱 **Custom dashboards** – Wall/tablet UI for daily use
- 🔒 **Self-hosted backend** – No third-party dependency
- 🔁 **Real-time sync** – MQTT/WebSocket powered
- 📦 **Expandable** – Camera feeds, HVAC, access control & more

---

## 🧰 Tech Stack

| Layer          | Tech                     |
|----------------|--------------------------|
| Firmware       | ESP32 + Arduino/CircuitPython  
| Communication  | MQTT + WebSocket  
| Backend        | FastAPI / Python  
| Frontend       | React / Next.js  
| Auth (optional)| Keycloak / JWT  
| Dashboard UI   | Wall-mounted tablet or smart display  

---

## 🛠 Repo Structure

```bash
bothomes/
├── firmware/         # ESP32 code
├── backend/          # FastAPI server
├── dashboard/        # React UI
├── wiring/           # Diagrams for home setup
├── ui-mockups/       # Tablet + mobile UI designs
├── LICENSE           # PolyForm Noncommercial
└── README.md         # You're reading this!
