# Arduino-smart-car
The Arduino-based smart car system operates using a combination of manual and
automated modes, facilitated by the integration of the L298N motor driver and an
ultrasonic sensor.
1. **Manual Mode:**
 - In manual mode, user input from a remote control or designated input device is
received by the Arduino microcontroller.
 - The Arduino processes the user's commands and sends appropriate signals to the
L298N motor driver to control the movement of the smart car.
 - Simultaneously, the ultrasonic sensor continuously measures distances in the smart
car's path.
2. **Obstacle-Aware Manual Control:**
 - While the smart car is in manual mode, the Arduino monitors the readings from the
ultrasonic sensor.
 - If the ultrasonic sensor detects an obstacle within a 10 cm range, the Arduino
interrupts the forward motion command, preventing the smart car from moving forward.
 - This obstacle-aware mechanism enhances safety by preventing collisions when
obstacles are detected during user-driven navigation.
3. **Automated Mode:**
 - In automated mode, the smart car relies on the ultrasonic sensor for autonomous
navigation.
 - The ultrasonic sensor continuously measures distances, and the Arduino processes
this data to detect obstacles.
 - When an obstacle is detected, the Arduino sends signals to the L298N motor driver
to adjust the smart car's direction and avoid the obstacle.
 - The smart car autonomously navigates its environment, making real-time decisions
based on feedback from the ultrasonic sensor.

smart car

![image](https://github.com/Lokeshdh46/Arduino-smart-car/assets/111194420/d62db4cf-8326-441d-8646-fd78d709edee)


all other information is given in report
