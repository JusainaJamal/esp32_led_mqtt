ESP32 MQTT LED Control
This project demonstrates an ESP32 microcontroller acting as a mini MQTT server (broker).

It allows other devices or applications (MQTT clients) to connect to the ESP32 and send commands over Wi-Fi to control the ESP32's onboard LED.

How it Works
The ESP32 connects to your Wi-Fi network and starts its own MQTT server.

MQTT clients (e.g., from your computer or phone) connect to the ESP32's IP address (like 192.168.1.100) using MQTT port 1883.

Clients can then publish messages to the led topic:

Publish on to turn the LED ON.

Publish off to turn the LED OFF.

The server also includes basic authentication (e.g., specific username/password combinations) for clients trying to connect.

This project is a great starting point for home automation or IoT applications where a central ESP32 can manage simple device controls via MQTT
