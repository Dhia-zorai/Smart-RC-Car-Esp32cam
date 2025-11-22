Skip to content
Navigation Menu
Dhia-zorai
Smart-RC-Car-Esp32cam

Type / to search
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Smart-RC-Car-Esp32cam
/
README.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing README.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
# Smart RC Car with AI Vision
---
>![work process](Documentation/carpic.webp)
---
---
>* A prototype for our car.*
---
A classic RC car transformed into a smart, web-controlled vehicle using IoT microcontrollers and computer vision. This project leverages an **ESP32-CAM** for live video streaming and an **ESP8266** for motor control, creating a platform that can be driven remotely via a web interface and enhanced with AI using Python's MediaPipe library.

---

## 🚀 Features

*   **Live Video Streaming:** ESP32-CAM streams real-time video feed securely over HTTP to PYTHON script.
*   **Web Control Interface:**  Browser-based controller for driving the car remotely from any device on the same network.
*   **Dual-Microcontroller Architecture:** Separates the demanding task of video streaming (ESP32-CAM) from motor control (ESP8266) for stable performance.
*   **AI-Powered Vision:** The video stream is processed by a Python script using Google's MediaPipe for advanced tasks like:
    *   Facial Detection
    *   Current mood Recognition
    *   Facial expressions Detection


---

## 🛠️ Hardware Components

| Component | Quantity | Purpose |
| :--- | :--- | :--- |
| RC Car Chassis | 1 | Base vehicle platform. |
| ESP32-CAM Module | 1 | Primary controller for live video streaming. |
| ESP8266 (e.g., NodeMCU) | 1 | Dedicated controller for driving motors. |
| Motor Driver (L298N) | 1 | Interfaces the ESP8266 with the car's motors. |
| DC Motors | 2 | Movement of the car. |
|Power Bank | 2 | power for ESP32-CAM & ESP8266 Microcontrollers. |
| AA Batteries | 4 | Powers the 2 DC Motors. |
| Jumper Wires | 9 | Connections. |


> **Note:** Using two separate power sources helped us prevent noise from the motors from crashing the sensitive ESP32-CAM module.

---

## 📋 Software & Prerequisites

*   **Arduino IDE:** For programming the ESP32-CAM and ESP8266.
*   **Arduino Core for ESP32:** (for ESP32-CAM)
*   **Arduino Core for ESP8266:** (for ESP8266)
*   **Python 3.13:** For the computer vision backend.
*   **Python Libraries:**
    *   `opencv-python`
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
Editing Smart-RC-Car-Esp32cam/README.md at main · Dhia-zorai/Smart-RC-Car-Esp32cam
