# Blindnav
BlindNav is an assistive navigation system for visually impaired individuals that combines Android-based GPS navigation, voice guidance, and an ESP32-powered wearable haptic feedback system. It provides directional vibration cues, route deviation detection, and obstacle detection to support safer and more independent mobility.
# BlindNav — Smart Navigation Assistant for the Visually Impaired

BlindNav is an assistive technology project designed to help visually impaired individuals navigate their surroundings more independently. It integrates an Android application with an ESP32-based wearable device to deliver real-time navigation instructions through voice guidance and directional haptic feedback.

### Key Features
- **Voice-Based Navigation:** Allows users to specify destinations using speech.
- **GPS Route Guidance:** Provides location-based navigation and route tracking.
- **Route Deviation Detection:** Identifies when the user moves away from the planned route.
- **Directional Haptic Feedback:** Uses left and right vibration motors to communicate navigation instructions.
- **Obstacle Detection:** Integrates a distance sensor to detect nearby obstacles.
- **Wireless Communication:** Transfers navigation commands from the Android application to the ESP32 over Wi-Fi.

### Tech Stack
- **Mobile Development:** Kotlin, Android Studio
- **Embedded Systems:** ESP32, Arduino framework
- **Sensors:** GPS, VL53L0X/VL53L1X time-of-flight distance sensor
- **Communication:** Wi-Fi, HTTP, JSON
- **Navigation:** OpenRouteService-based routing and route deviation logic

### System Architecture
The Android application handles destination input, GPS tracking, route calculation, and navigation decisions. It sends navigation commands wirelessly to an ESP32, which controls the wearable vibration motors to provide directional feedback. Obstacle detection adds another layer of awareness to the navigation system.

### Objective
To develop an accessible, wearable, and affordable navigation solution that combines mobile software, embedded hardware, and sensor technology to improve independent mobility for visually impaired users.


## Project Gallery

### BlindNav Prototype
![BlindNav Prototype](<img width="333" height="746" alt="image" src="https://github.com/user-attachments/assets/1aa56732-5a66-439c-b447-4bb61976215b" />
)

### Android Application
![BlindNav Android App](<img width="483" height="730" alt="image" src="https://github.com/user-attachments/assets/80bc0815-5985-4051-bcc6-f01e5089eb7c" />
)

