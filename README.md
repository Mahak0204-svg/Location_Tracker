# 📍 ESP32 Location Tracker with Live Google Maps
🚀 Real-Time GPS Tracking on Web Browser via ESP32 + NEO-6M + WiFi
<div align="center"> <img src="https://github.com/Mahak0204-svg/Location_Tracker/blob/a5c51ba808b166357f8e21a62f6112419ca97187/Web%20Interface.jfif" alt="ESP32 Location Tracker Banner" width="80%"> </div>


**🔥 Project Overview**

This project turns your ESP32 into a real-time GPS location tracker, displaying live coordinates on an embedded Google Map served via WiFi. It uses the NEO-6M GPS module to get the current geolocation, and the ESP32 acts as a web server to show your live location in the browser—perfect for IoT, vehicle tracking, and personal locator systems.

**🧠 Features**

🌍 Live location updates on Google Maps

📡 NEO-6M GPS integration with latitude & longitude extraction

🔌 ESP32 WiFi access point/server mode

📱 Mobile-friendly web interface

⚡ Lightweight and responsive

**🛠️ Components Used**

Component	Description
* ESP32 Dev Module	WiFi + Bluetooth SoC
* NEO-6M GPS Module	Provides real-time coordinates
* Jumper Wires + Breadboard	For prototyping setup
* Power Supply	USB or Li-Ion battery
  
# 🔌 Circuit Diagram

![Circuit Diagram](https://github.com/Mahak0204-svg/Location_Tracker/blob/a5c51ba808b166357f8e21a62f6112419ca97187/esp32-gps-Circuit_Diagram.png)

**🎯 How It Works**

* ESP32 connects to your WiFi using SSID & Password.
* GPS module sends coordinates to ESP32 using Serial communication.
* ESP32 serves a simple HTML page with a Google Maps embed.
* Your current coordinates are plotted on the map in real-time!


# 🎥 Demo Video

You can download the project demo video here: [Radar Demo](https://github.com/Mahak0204-svg/Location_Tracker/blob/a5c51ba808b166357f8e21a62f6112419ca97187/Location%20racker%20Demo%20video)

**🔧 Setup Instructions**

* Upload the provided Arduino code to your ESP32.
* Connect the GPS module using the circuit diagram.
* Connect to the same WiFi as your ESP32.
* Enter the ESP32’s IP address (shown in Serial Monitor) in your browser.
* Watch your location update on the map!

**💡 Use Cases**

🚗 Vehicle tracking

👤 Personal safety device

📦 Parcel & logistics tracking

🚶 Fitness or adventure tracking

**🔐 Notes**

Google Maps API key required (free tier available).

Make sure to handle GPS cold start delay (may take up to 1–2 mins initially).

**⭐ Connect With Me**

📧 mahaksharma0204@gmail.com

# 🏁 Star this repository if you liked it and feel free to fork or contribute! 🌟
