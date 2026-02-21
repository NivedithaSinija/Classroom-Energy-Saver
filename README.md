# Classroom-Energy-Saver
An IoT-based smart classroom energy saver using ESP32 that automates lighting and alerts based on motion (PIR), ambient light (LDR), and temperature (DHT22). It includes manual override controls, real-time LCD display, and an ECO score to monitor energy efficiency.
The system integrates multiple sensors and components such as a PIR motion sensor, LDR (Light Dependent Resistor), and DHT22 temperature sensor to automate decision-making. When the system is in automatic mode, the LDR detects ambient light levels and turns ON the lights only when the surroundings are dark. The PIR sensor monitors human presence—if no motion is detected while lights are ON, a buzzer alert is triggered to indicate possible energy wastage.

A manual override feature using push buttons allows users to control the system directly. One button enables smart (automatic) mode, while another activates a full ON mode where all lights remain ON regardless of sensor input. LED indicators provide clear visual feedback about the current mode of operation.

Additionally, the DHT22 sensor monitors temperature and adjusts the brightness of an LED accordingly using PWM, demonstrating adaptive energy usage based on environmental conditions.

An ECO score is continuously calculated based on how long the system keeps devices turned OFF compared to total runtime. This score is displayed on an I2C LCD display, giving real-time feedback on energy efficiency and encouraging responsible usage.

Overall, this project combines automation, monitoring, and user control to create an efficient and practical solution for energy conservation in classrooms.
