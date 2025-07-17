This project demonstrates the implementation of a lightweight, real-time IoT communication
system using the MQTT (Message Queuing Telemetry Transport) protocol. It utilizes a Raspberry
Pi as an MQTT broker and an ESP8266 microcontroller as a client, forming a foundational setup
for efficient machine-to-machine (M2M) communication. The primary goal is to establish and
simulate reliable topic-based messaging between devices over a local network.
The Raspberry Pi, running a full MQTT broker (e.g., Mosquitto), manages all message routing,
while the ESP8266 acts as a publisher or subscriber depending on the use case. Topics were
created and monitored using both CLI tools and a mobile MQTT client app, allowing for intuitive
control and real-time data observation. Additionally, RealVNC was used for remote desktop
access to the Raspberry Pi, enabling seamless management and testing from different locations.
Through this setup, I was able to successfully publish and subscribe to topics, visualize message
transfers, and simulate IoT scenarios such as sensor data streaming or device control. This
project serves as a hands-on introduction to MQTT architecture, and lays the groundwork for
future development of smart automation systems, remote monitoring, and IoT-based
applications.
