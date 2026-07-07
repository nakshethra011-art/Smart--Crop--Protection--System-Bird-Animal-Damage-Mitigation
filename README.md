# Smart--Crop--Protection--System-Bird-Animal-Damage-Mitigation
An ESP8266-based smart automation system to protect crops from birds and animals without harming them.
How it works:
An ultrasonic sensor continuously monitors for animal/bird presence near the farmland. When an object is detected within range (under 15 cm threshold), the system activates a buzzer and water pump to safely deter the animal, and sends an SMS alert via a GSM module. Real-time distance readings and system status are displayed on a 16x2 I2C LCD screen.
Tech stack:
	•	Microcontroller: ESP8266 (NodeMCU)
	•	Sensors: Ultrasonic sensor (HC-SR04 or similar) for distance/presence detection
	•	Actuators: Water pump, buzzer
	•	Communication: GSM module (SIM800/similar) via SoftwareSerial for SMS alerts
	•	Display: 16x2 I2C LCD for real-time status
Key features:
	•	Real-time ultrasonic distance monitoring
	•	Automatic water pump activation on detection (eco-friendly deterrent)
	•	SMS alert notification via GSM
	•	LCD status display
