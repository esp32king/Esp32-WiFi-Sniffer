# Esp32-MITM
 

### 🚀 ESP32 Advanced Captive Portal + DNS Interceptor + BLE Auto-Action
🔥 Advanced level WiFi Phishing 
```
LIVE DNS intercepting + Captive portals + BLE HID (Combo)
```
Created by ❤️ Krishna UPX61

<img src="https://raw.githubusercontent.com/esp32king/Esp32-WiFi-Sniffer/refs/heads/main/Files/pkmkb.png"></img>
LIVE Intercepting..
```
DNS intercepting + Captive portals + BLE HID (Combo)
```
### ⭐ Overview
<iframe width="100%" height="600"
src="https://www.youtube.com/embed/cJmxkM5E3FE"
title="YouTube video"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
allowfullscreen>
</iframe>

This project turns your ESP32 into a powerful WiFi portal system with:

✨ Captive Portal (auto-opens on mobile & laptop)

✨ WiFi Password Popup → Instagram Login Page

✨ Credentials Logging (WiFi + Instagram)

✨ DNS Domain Logger (live visited domain monitor)

✨ Admin Panel with delete logs + credentials table

✨ BLE Keyboard Auto-Type (opens Instagram automatically)

✨ Real-time redirect for all devices

✨ Beautiful UI + Neon Effects

✨ Super fast, optimized, no lag

### 🌐 Features
🔐 1. Captive Portal Login Flow
```
When any device connects to your WiFi:

Auto popup → "WiFi Router Error"

User enters WiFi password → Saved

Then it forces Instagram login page

After login → User gets normal internet ✔️ 
```

### 📡 2. DNS Live Intercept

Every opened website is logged with:

Method (GET/POST)

Full URL

Timestamp

Admin panel shows all visited sites in real time.

### 🎛 3. Admin Panel

Open:
```
http://<your-esp-ip>/admin
```

You get:

- ✔️  WiFi password log

- ✔️  Instagram credentials log

- ✔️ User-Agent

- ✔️ Timestamp

- ✔️ Delete button

- ✔️ Clear DNS logs

- ✔️ Auto-refresh DNS viewer

- ✔️ Neon GitHub button

### 🎹 4. BLE Keyboard Auto Action

When device connects via Bluetooth:

Auto opens browser

Auto types Instagram link

Auto opens your profile

Perfect for automation demos.

### 🛠 Hardware Required

ESP32 Dev Module

USB cable

Any phone/PC to connect to WiFi

Optional: BLE-supported mobile/laptop

### 📦 Libraries Needed

Make sure these libraries are installed:
```
WiFi.h  
WebServer.h  
DNSServer.h  
WiFiUdp.h  
BleKeyboard.h
```
### 🚀 Installation
```
Open Arduino IDE

Select ESP32 Dev Module

Paste the code

Flash → Done
```
📲 Usage Flow
Step 1️⃣

Phone connects to hotspot ESP NOW

Step 2️⃣

Captive portal auto-opens

Step 3️⃣

User enters WiFi password → Saved

Step 4️⃣

Instagram login shows → Credentials saved

Step 5️⃣

DNS tracking starts + internet unlock

### 👨‍💻 Admin Panel Preview

- ✔️ Saved WiFi passwords

- ✔️ Saved Instagram users/passwords

- ✔️ Recent visited websites

- ✔️ Delete row option

- ✔️ Clear DNS logs

- ✔️ Everything is neat & responsive.

- ✔️ 📘 BLE Automation

- ✔️ Once BLE device connects:

Alt+Tab → Open browser

Ctrl+T → New tab

Ctrl+E → URL bar

Types:

https://instagram.com/krishna_upx61


Perfect for presentations 💙

### 📁 Project Author

Made with ❤️ by 

   Krishna UPX61




Instagram: @krishna_upx61

GitHub: github.com/esp32king

### ⭐ Give a Star

If this project helped you → Give it a ⭐ on GitHub! 🙌
