1. Introduction
   
Water scarcity and inefficient water management are critical global issues. To address these concerns, an automatic water level indicator and controller system is developed using a PIC16F887 microcontroller, ultrasonic sensor, alarm system, LED bulbs, 1602A LCD Module, one-channel relay module, power supply components, and a motor for tank refilling. The system monitors water levels in a well and a storage tank, providing automatic control to refill the tank when needed. This ensures optimal water management and prevents overflow or dry running of the motor.
3. Scope
The scope of this project includes:
•	Real-time monitoring of water levels using an ultrasonic sensor.
•	Low-water level detection: An alarm will activate after 90 seconds when the water level is low.
•	Visual indications: LED bulbs will turn on when water runs out in the well.
•	Elapsed time display: The 1602A LCD Module will show the duration of water level status.
•	Automated water control: A one-channel relay module will automatically switch the motor ON/OFF to maintain adequate water levels.
•	Stable operation: The system includes essential components such as resistors, capacitors, and a potentiometer to ensure smooth and stable functionality.
•	Reliable power supply for continuous system operation.
4. System Components
The system comprises the following components:
•	PIC16F887 Microcontroller: The brain of the system, processing sensor data and controlling outputs.
•	Ultrasonic Sensor: Measures water levels with high precision.
•	Alarm System: Activates after 90 seconds if the water level is critically low.
•	LED Bulbs: Indicate a low water level in the well.
•	1602A LCD Module: Displays elapsed time and real-time water levels.
•	One-Channel Relay Module: Controls the motor automatically.
•	Power Supply: Ensures continuous operation.
•	Resistors, Capacitors, and Potentiometer: Provide circuit stability.
•	Motor: Pumps water into the tank as required.
5. Working Principle
1.	The ultrasonic sensor continuously monitors the water level in the well and storage tank.
2.	If the water level in the well is low, an LED bulb turns on, indicating water shortage.
3.	If the water level in the tank drops below the threshold, the one-channel relay module automatically turns on the motor to refill the tank.
4.	If the water level remains low for 90 seconds, an alarm is triggered to alert users.
5.	The 1602A LCD Module displays the elapsed time of the system operation.
6.	Once the tank reaches the desired level, the motor automatically turns off, preventing overflow.
5. Circuit Design
The system is designed using:
•	Microcontroller connections: The PIC16F887 is interfaced with the ultrasonic sensor, alarm, LED bulbs, relay module, LCD display, and motor.
•	Sensor placement: The ultrasonic sensor is positioned at the top of the tank to measure water levels.
•	Power distribution: A regulated power supply is used to power all components efficiently.
•	Relay Control: The one-channel relay is connected to the microcontroller and motor to automate water flow.
6. Advantages
•	Prevents water wastage by automating motor control.
•	Enhances water management with real-time monitoring.
•	Protects motor longevity by avoiding dry runs.
•	User-friendly with clear LED and LCD indicators.
•	Cost-effective and energy-efficient design.
7. Conclusion
This automatic water level indicator using PIC16F887 and an ultrasonic sensor provides a smart solution for water conservation and efficient resource management. The system ensures automated water refilling, timely alerts, and real-time level monitoring, making it ideal for households and industrial applications. Future enhancements may include IoT-based remote monitoring and solar-powered operation to make it more sustainable and efficient.



![image](https://github.com/user-attachments/assets/a185946b-925c-4bfc-9ce1-a688664df56f)

![image](https://github.com/user-attachments/assets/99ddfb2c-8be7-4813-b708-943fb3a23140)




