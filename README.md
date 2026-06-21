# TASK-1
Motor Control Using PWM with Obstacle Detection (Embedded Systems)

Project Overview :
      This project demonstrates motor speed control using PWM (Pulse Width Modulation) combined with obstacle detection for safety.
      When an obstacle is detected within a set distance, the motor speed is reduced or stopped automatically.
This project was completed as Task 1 of the Embedded Systems Internship at Alfido Tech.

Objectives :

Control motor speed using PWM
Detect obstacles using a sensor
Implement real-time response based on sensor input
Understand hardware–software interaction in embedded systems

Components Used : 

Microcontroller (Arduino )
DC Motor
Motor Driver Module (L293D)
Obstacle Sensor (Ultrasonic)
Jumper Wires
Power Supply

Working Principle :

PWM is used to control the speed of the motor by varying the duty cycle.
The obstacle sensor continuously monitors the distance.
If an obstacle is detected within the threshold distance:
   Motor speed is reduced or stopped
If no obstacle is detected:
   Motor runs at the set PWM speed
This ensures safe motor operation in dynamic environments.

Logic Explanation :

Initialize motor control and sensor pins
Generate PWM signal for motor speed control
Read distance/sensor values continuously
Compare sensor value with threshold
Control motor speed based on detection result

How to Run :

Connect components as per the circuit
Upload the code to the microcontroller
Power the circuit
Observe motor speed changes based on obstacle distance

Output :

Motor speed varies using PWM
Motor stops or slows down when obstacle is detected
Serial Monitor displays sensor readings (if enabled)

Skills Gained :

PWM motor control
Sensor interfacing
Embedded C programming
Real-time hardware control
Debugging using Serial Monitor

Internship :
Completed as part of Embedded Systems Internship – Alfido Tech

