# 👋 Hi there!

This is a simple program for ESP32 that uses Websockets to send and receive audio data. It listens for a button press, and when pressed it sends a request to the server. The server then responds with a timestamp, and the ESP32 enters speaking mode. The ESP32 then begins streaming audio data to the server until the button is released, at which point it enters idle mode again.

# ✨ Features:

Uses Websockets to send and receive audio data.
Streams audio data from ESP32 to server.
Uses a button press to trigger the streaming of audio data.
Has 3 states: idle, listening, and speaking.
Handles connection and disconnection events.

# 🚀 Getting Started

Download and install the Arduino IDE.
Install the ESP32 board in the Arduino IDE.
Install the "ArduinoWebsockets" and "Button2" libraries.
Connect an ESP32 to your computer via USB.
Open the "WebSocketClient" sketch in the Arduino IDE.
Set the SSID and password for your WiFi network.
Set the Websockets server host and port.
Compile and upload the sketch to the ESP32.
Open the Serial Monitor to see the ESP32 connecting to the WiFi network and the Websockets server.
Press the button to begin streaming audio data to the server.
# 💡 Usage

Press the button on the ESP32 to begin streaming audio data to the server.
Release the button to stop streaming audio data to the server.
# 📝 Note

This program has been tested on an ESP32 board.
This program uses the ArduinoWebsockets and Button2 libraries.
This program uses a button to trigger the streaming of audio data.
This program requires a Websockets server to receive audio data.
This program is for demonstration purposes only and is not intended for use in production environments.
# 📚 References

ArduinoWebsockets library: https://github.com/gilmaimon/ArduinoWebsockets

Button2 library: https://github.com/LennartHennigs/Button2

ESP32 board: https://www.espressif.com/en/products/socs/esp32/overview
