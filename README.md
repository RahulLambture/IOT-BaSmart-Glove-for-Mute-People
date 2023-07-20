# IOT-BaSmart-Glove-for-Mute-People
The "IOT Based Smart Glove for Mute People" is an innovative and impactful project aimed at empowering individuals with speech disabilities. This project combines technology with the beauty of hand gestures to create a smart glove that enables communication for the mute community.

Project Title: Gesture-Controlled Alert System using MPU6050 and Flex Sensors
Introduction:

This Arduino-based project utilizes MPU6050 (accelerometer and gyroscope sensor) and flex sensors to create a gesture-controlled alert system. The system is designed to detect hand movements and gestures, providing specific alerts based on the detected gestures. It is particularly helpful for mute individuals to communicate essential needs in real-time.

Working:

The system comprises four flex sensors, each assigned to different gestures, and an MPU6050 sensor to detect any acceleration or tilt of the hand. The flex sensors provide analog input based on the bending of fingers, and the MPU6050 measures hand orientation.

Upon receiving input from the sensors, the Arduino board processes the data and determines the corresponding gesture. If a specific gesture is recognized, the system triggers an appropriate alert. For example, bending one finger might indicate a need for food, while another gesture could signify a request for water.

Description:

This project demonstrates how advanced sensor technologies can be integrated to enhance communication and accessibility. It aims to empower mute individuals by enabling them to express their needs effortlessly through gestures.

Components Used:
Arduino UNO
MPU6050 Sensor (accelerometer and gyroscope)
Four Flex Sensors
LEDs for Indication
Gesture-Alert Mapping:
Flex Sensor 1: Food Alert
Flex Sensor 2: Water Alert
Flex Sensor 3: Help Alert
Flex Sensor 4: Custom Alert (Can be programmed for a specific need)
Instructions:
Connect the flex sensors and MPU6050 to the Arduino board as specified in the initial comments of the code.
Upload the provided code to the Arduino board using the Arduino IDE.
Calibrate the flex sensors and MPU6050 if required, using the "checkSettings()" function in the code.
Power up the system and wear the glove equipped with the flex sensors.
As you bend your fingers or make specific hand movements, the system will recognize gestures and trigger corresponding alerts.
Note:
The sensitivity of flex sensors and MPU6050 can be adjusted as needed.
Customize the custom alert (Gesture assigned to Flex Sensor 4) for specific user requirements.
Enjoy Empowering Silence with Gesture-Controlled Alerts! 🤝🧤 #GestureAlertSystem #EmpoweringSilence #ArduinoProject
