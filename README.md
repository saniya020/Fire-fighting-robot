🔥 Fire-Fighting Robot

Description
An autonomous fire-detection and extinguishing robot designed to identify flames, navigate toward them, and suppress small fires without human intervention. This project demonstrates core concepts of embedded systems, robotics, sensor interfacing, and automation for safety applications.

📘 *Overview*
Fire accidents often occur in areas that are dangerous or inaccessible for humans. The Fire-Fighting Robot provides a safer alternative by using sensors and programmed logic to detect a fire and act automatically. Using an Arduino UNO as the main controller, the robot tracks the direction of the flame, moves toward it, and activates a water pump/fan mechanism to extinguish it.

🛠 *Components Used*

Arduino UNO
3 × IR Flame Sensors
L293D Motor Driver Module
BO Motors
Servo Motor
Water Pump / Fan (Based on design)
18650 Li-ion Battery
Car Chassis
Mini Breadboard
Connecting Wires

⚙️*Working Principle*

1. Flame Detection:
Three flame sensors continuously scan the surroundings. When a flame is detected, the sensor sends a signal to the Arduino.

2. Direction Decision:
Based on which sensor detects the fire (left, right, or center), the Arduino commands the L293D driver to move the motors accordingly.

3. Navigation:
The robot moves toward the fire, adjusting direction as needed.

4. Extinguishing:
Once close enough, the robot activates its servo-controlled water pump/fan to suppress the flame until it is under control.

🎯 *Expected Output*

1. Detects small indoor fires.
2. Automatically moves toward the flame source.
3. Activates extinguishing system without human input.

💡 *Applications*

1. Hazardous or narrow locations
2. Server rooms and control rooms
3. Disaster site assistance
4. Educational robotics and safety automation projects

🚀 *Future Enhancements*

1. IoT-based monitoring and alerts
2. Wireless/manual control mode
3. Improved obstacle avoidance
4. Autonomous navigation using sensors or mapping

