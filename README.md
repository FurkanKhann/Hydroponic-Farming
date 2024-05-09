<h1 align="center" id="title">Hydroponic Farming Monitoring System</h1>

<p align="center"><img src="https://i.postimg.cc/jCV3Svb1/img1.jpg" alt="project-image"></p>

<p id="description">This repository contains the code and documentation for an IoT and Arduino-based project focused on monitoring key parameters in hydroponic farming systems. Overview Hydroponic farming is a method of growing plants without soil using nutrient-rich water solutions. Monitoring various environmental parameters is crucial to ensure optimal growth conditions for plants. This project aims to create a monitoring system that tracks temperature humidity pH levels TDS (Total Dissolved Solids) in water light intensity water level and water temperature.</p>

<h2>Components</h2>

1-Arduino Uno  
2-DHT11 Temperature and Humidity Sensor  
3-TDS Sensor  
4-pH Meter Sensor  
5-Light Intensity Sensor  
6-Water Level Sensor  
7-Digital Water Temperature Sensor  
8-Buzzer<h2>Installation</h2>

1-Connect the sensors and components to the Arduino Uno board as per the circuit diagram.  
2-Upload the provided Arduino code (hydroponic\_monitoring.ino) to the Arduino board using the Arduino IDE or any compatible IDE.  
3-Ensure all connections are secure and the sensors are placed appropriately in the hydroponic system.<h2>Usage</h2>

1-Power on the Arduino board.  
2-The sensors will start reading environmental data such as temperature humidity pH TDS light intensity water level and water temperature.  
3-The system will continuously monitor these parameters and sound an alert (activate the buzzer) if any parameter goes out of the specified range. Use the serial monitor in the Arduino IDE or any serial monitor application to view the real-time data and alerts.<h2>Alerts:</h2>

1-Temperature out of range.  
2-Humidity out of range pH value out of range.  
3-TDS value out of range.  
4-Water level is low.  
5-Light intensity is too low.  
6-Water temperature out of range.

<h2>🚀 Demo</h2>

[https://drive.google.com/file/d/1Gq4etZFSIsOmtQXdjFWsyyTirqsmblgV/view?usp=sharing](https://drive.google.com/file/d/1Gq4etZFSIsOmtQXdjFWsyyTirqsmblgV/view?usp=sharing)
