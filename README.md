## **Line Follower Robot with Obstacle Avoidance**

This robot follows a black line and avoids obstacles. It was assembled using the video tutorial below:

[https://www.youtube.com/watch?v=4PQgjjOqJa4](https://www.youtube.com/watch?v=4PQgjjOqJa4)

presentation - 

## **Project Description**

This project is an autonomous mobile robot that moves along a black line using infrared sensors.
If an obstacle appears in its path, the robot detects it, performs an avoidance maneuver, and then returns back to the line.

P.S. 
In our project, we added an additional feature — a **Bluetooth module** that allows the robot to be controlled using **voice commands through a smartphone**.
This expands the robot’s capabilities: it can operate in **autonomous mode** (following the line) as well as in **manual mode**, where voice commands control its movement **to the left, right, forward, and backward**.

---

The project demonstrates:

* operation of the motor driver
* reading data from IR line sensors
* obstacle detection
* direction control
* simple autonomous behavior logic

## **Components Used**

* **Arduino UNO/Nano** (any compatible controller)
* **Motor Driver L298N**
* **Two DC motors + wheels**
* **Infrared line sensors (2 pcs.)**
* **Obstacle sensor (Ultrasonic HC-SR04 or IR)**
* **Battery pack**
* **Wires, mounts, bolts, chassis**
* **Breadboard**



---

##  Robot Assembly

1. Assemble the chassis and attach the motors.
2. Install the L298N motor driver.
3. Connect the motors to the L298N outputs.
4. Connect the line sensors to the Arduino analog/digital pins.
5. Mount the obstacle sensor at the front.
6. Install the Bluetooth module.
7. Connect the Bluetooth module to the Arduino.
8. Connect the power supply (battery → motor driver → Arduino).
9. Upload the Arduino code.

**Main functions of the code:**

* Reading IR line sensors
* Obstacle detection
* Motor control logic: movement, turning, stopping
* Obstacle avoidance algorithm

---

## Result

The robot successfully performs:

* precise line following
* detection of line gaps
* obstacle detection
* obstacle avoidance with return to the line

The result demonstrates the fundamentals of robotics: sensor integration, microcontroller programming, mechanics, and control logic.

---

##  Possible Improvements

* add more line sensors for higher accuracy
* improve the obstacle avoidance algorithm
* replace the motor driver with a more compact module
* switch to Li-ion batteries
* create a custom 3D-printed body

---

##  Authors

Project contributors:

* **Berdibekova Zhasmina**
* **Subanova Milena**
* **Kasmaly kyzy Fatima**

---

