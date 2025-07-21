# WiFiVisionCar
WiFiVisionCar is an ESP32-based remote-controlled car with a camera, allowing real-time video streaming and movement control via a web interface. The project integrates PWM motor control, a pan-tilt mechanism for the camera, and an interactive HTML dashboard for seamless navigation. Ideal for surveillance, robotics, and IoT applications.

# 🚗 ESP32-CAM Based Wi-Fi Controlled VisionCar
This project showcases a Wi-Fi-controlled camera car using the ESP32-CAM module. It allows real-time video streaming over a local network and basic directional control via a web interface. Ideal for surveillance, IoT experimentation, and embedded systems learning.

## 🔧 Features
📷 Live video streaming using ESP32-CAM

🎮 Web-based control panel for direction control (forward, backward, left, right, stop)

📡 Connects over Wi-Fi (station or AP mode)

🔋 Portable and battery-powered

💻 Embedded web server with control buttons

## 🧠 Tech Stack
ESP32-CAM module (AI-Thinker)

L298N Motor Driver

DC Motors + Chassis

Web Server hosted on ESP32

Arduino IDE for programming

Optional: Servo motor for camera pan/tilt (if used)

## 🚀 How It Works
ESP32 hosts a web server on the local network.

User connects to the ESP32 IP via browser.

Live camera feed and directional buttons are available on the web interface.

Clicking buttons sends HTTP requests to control motors.

## 🔌 Wiring Overview
ESP32-CAM -> Motor driver (via GPIOs)

Power supply -> ESP32-CAM + Motors

Camera stream via onboard OV2640 module

## 📌 Ensure 5V regulated supply for ESP32 and sufficient current for motor driver.

## 🛠 Setup & Installation
Install Arduino IDE and ESP32 board manager.

Upload the code using FTDI adapter (connect RX/TX and GPIO0 to GND).

Modify Wi-Fi credentials in the sketch.

Assemble the car and upload the sketch.

Open browser and access ESP32 IP to start driving!
