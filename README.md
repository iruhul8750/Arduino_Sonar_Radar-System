# Ultrasonic Radar System using Arduino & Processing

## Project Overview
This project is an **Ultrasonic Radar System** built using an **Arduino, Ultrasonic Sensor (HC-SR04), and a Servo Motor.** It visualizes detected objects in real-time using **Processing IDE.** The radar scans an area by rotating the sensor and plots the detected objects on a graphical interface.

## Components Required
- Arduino Uno  
- HC-SR04 Ultrasonic Sensor  
- Servo Motor (SG90 or MG995)  
- Jumper Wires  
- Processing IDE (for graphical visualization)  

## Working Principle
1. The servo motor moves from **15° to 165°** and then back.  
2. At each step, the **ultrasonic sensor** emits a sound pulse and measures the time it takes to bounce back.  
3. The distance is calculated using **speed of sound** and plotted on the radar screen in **Processing IDE.**  

## Installation & Usage
### **Arduino Code Upload**
1. Install the **Arduino IDE** and necessary drivers.
2. Connect the components as per the circuit diagram.
3. Upload the Arduino code to your board.

### **Processing Setup**
1. Install **Processing IDE**.
2. Open the Processing script and ensure the correct **COM port** is set.
3. Run the script to visualize real-time object detection.

## Features
- **Real-time object detection** using ultrasonic waves.
- **Graphical representation** in Processing.
- **Adjustable scanning angles**.
- **Easy to modify** for custom applications.

## Future Improvements
- Integration with **AI for object classification**.
- Support for **multiple sensors** to enhance accuracy.
- Wireless communication using **Bluetooth/WiFi**.

## Author
**Ruhul Islam**  
Feel free to reach out for any questions or improvements!

---
This project is open-source and can be improved further with additional sensors and AI-based object detection.
