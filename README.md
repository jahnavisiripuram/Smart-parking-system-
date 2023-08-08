 Smart Parking System Project using Arduino, IR Sensor, and Servo Motor. Here we will discuss Introduction to Smart Parking System Project,
 Project Concept, Block Diagram, Components Required, Working Principle, and Arduino code.
 A smart parking system is a technologically advanced solution designed to optimize and enhance the parking experience for both drivers and parking operators. Traditional parking management can often be inefficient, leading to congestion, wasted time, and frustration for drivers. A smart parking system addresses these issues by utilizing various technologies to streamline the parking process and provide real-time information to users.

The primary goal of a smart parking system is to make the entire parking process more convenient, efficient, and user-friendly. This is achieved through the integration of sensors, data analytics, mobile applications, and other technologies to provide accurate and up-to-date information about parking availability, pricing, and navigation.

# components used 
Arduino Nano or Arduino Uno	1
USB Cable for Arduino 	1
IR Sensor	6
Sg90 Servo Motor	1
9V power supply	1
PCB board or Breadboard 1
Connecting wires-As required in the circuit diagram
# Working Principle
After assembling all components according to the circuit diagram and uploading the code to the Arduino board. Now place the sensors and servo 
motor at accurate positions.

There are four parking slots in this project, IR sensor-3, 4, 5, and 6 are placed at slot-1, 2, 3, and 4 respectively. IR sensor-1 and 2 are placed at the entry and exit gate respectively and a servo motor is used to operate the common single entry and exit gate. The LCD display is placed near the entry gate.

The system used IR sensor-3, 4, 5, and 6 to detect whether the parking slot is empty or not and IR sensor-1, and 2 for detecting vehicles arriving or not at the gate.

In the beginning, when all parking slots are empty, then the LCD display shows all slots are empty.

When a vehicle arrives at the gate of the parking area then the IR sensor-1 detects the vehicle and the system allowed to enter that vehicle by opening the servo barrier. After entering into the parking area when that vehicle occupies a slot then the LED display shows that the slot is full. In this way, this system automatically allows 4 vehicles.

In case the parking is full, the system blocked the entrance gate by closing the servo barrier. And the LED display shows that slot-1, 2, 3, and 4 all are full.

When a vehicle leaves a slot and arrives at the gate of the parking area then the IR sensor-2 detects that vehicle and the system open the servo barrier. Then the LED display shows that the slot is empty. Again the system will allow entering a new vehicle.
