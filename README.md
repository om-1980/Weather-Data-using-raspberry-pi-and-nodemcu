# Weather-Data-using-raspberry-pi-and-nodemcu
In this DIY weather monitoring project, a Raspberry Pi and NodeMCU (ESP8266) are employed to collect and transmit real-time weather data. Connected to the Raspberry Pi, sensors such as DHT11 or DHT22 for temperature and humidity, and optionally BMP180 or BMP280 for atmospheric pressure, capture environmental conditions. The NodeMCU, equipped with these sensors, reads the data and communicates it to the Raspberry Pi, either directly or through an optional MQTT broker. Users can access the weather information via a local web server hosted on the Raspberry Pi or explore options to store and visualize data for future analysis. This hands-on project not only provides valuable insights into creating an IoT weather station but also encourages experimentation with various sensors and communication protocols.

# Components:
- Raspberry Pi
- NodeMCU (ESP8266)
- DHT22 Sensor
- Jumper Wires
- Breadboard
- 1 LED

# Setup Steps:
- Hardware Setup:
    - Connect DHT11 or DHT22 for temperature and humidity to the Raspberry Pi.
    - Optionally, connect BMP180 or BMP280 for atmospheric pressure.
- NodeMCU Programming:
      Install Arduino IDE and add ESP8266 board support.
Write a program to read sensor data using the NodeMCU.
Upload the program to the NodeMCU.
MQTT Communication (Optional):

Install an MQTT broker like Mosquitto on the Raspberry Pi.
Modify NodeMCU program to publish sensor data to the MQTT broker.
Write a Python script on the Raspberry Pi to subscribe to MQTT topics and receive the data.
Data Display or Storage:

Create a local web server on the Raspberry Pi to display sensor data.
Optionally, store data in a database for analysis.
Consider using IoT platforms like ThingSpeak or Blynk for visualization.
Power Considerations:

Ensure stable power supply for both Raspberry Pi and NodeMCU.
Consider external power sources or batteries if needed.
Security Considerations:

Implement security measures, such as HTTPS for the web server and username/password for MQTT, for remote access.
Testing:

Thoroughly test the setup to ensure accurate sensor readings and stable communication.
Documentation and Compliance:

Document your setup and configurations.
Adhere to legal and regulatory requirements in your region.
