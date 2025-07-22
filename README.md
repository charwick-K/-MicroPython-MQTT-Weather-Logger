# 🌦️ MicroPython MQTT Weather Logger

This project simulates an IoT-based weather station using **ESP32**, **MicroPython**, and **MQTT**, built and tested on the [Wokwi simulator](https://wokwi.com/). It reads temperature and humidity data from a **DHT22 sensor** and publishes it to an MQTT broker in real time.

## 🚀 Features

- ESP32 programmed with MicroPython
- DHT22 sensor for temperature and humidity
- MQTT communication using `umqtt.simple`
- Simulated Wi-Fi connection via Wokwi
- Real-time data publishing to MQTT broker

## 🧰 Components Used

- ESP32 (Wokwi virtual board)
- DHT22 sensor
- MQTT Broker: [mqttdashboard.com](http://broker.mqttdashboard.com)
- MicroPython firmware

## 📡 MQTT Setup

To view the data:
1. Go to [HiveMQ WebSocket Client](http://www.hivemq.com/demos/websocket-client/)
2. Click **Connect**
3. Add a new topic subscription: `wokwi-weather`
4. Run the simulation and observe live updates

## 🧪 Simulation Instructions

1. Open the project in [Wokwi](https://wokwi.com/)
2. Click **Start Simulation**
3. Modify the DHT22 sensor values to simulate weather changes
4. Watch the MQTT messages update in HiveMQ

## 📽️ Demo

Screen recording of the simulation and MQTT output:  
The Recording Has been Uploaded Above in repository.Kindly Check.

## 🧠 Credits

- Developed and simulated using [Wokwi](https://wokwi.com/)
- MQTT broker: [mqttdashboard.com](http://broker.mqttdashboard.com)

## 📜 License

This project is licensed under the MIT License.
