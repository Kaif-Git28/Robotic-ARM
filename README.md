# Bluetooth-Controlled Robotic Arm

## Overview
The **Bluetooth-Controlled Robotic Arm** is an innovative project designed to provide remote manipulation capabilities through a custom mobile application. Utilizing Arduino UNO, servo motors, and Bluetooth technology, this robotic arm can perform a variety of tasks, showcasing the power of automation in a fun and interactive way.

## Features
- **Wireless Control**: Operate the robotic arm from your smartphone via Bluetooth.
- **Intuitive User Interface**: Custom mobile app built with MIT App Inventor for easy interaction.
- **Precise Movements**: Control each joint of the arm with dedicated buttons, enabling accurate manipulation.
- **Flexible Design**: Modify the Arduino code and mobile app to fit specific project needs or enhancements.

## Components
To build this robotic arm, the following components are required:
- **Arduino UNO**: The main control unit for processing inputs and driving the servos.
- **HC-05 Bluetooth Module**: Enables wireless communication between the smartphone and Arduino.
- **Servo Motors (5x)**: Provide movement for the arm's joints.
- **Power Supply**: Powers the Arduino and the servo motors.
- **Jumper Wires**: For connecting the various components.
- **Mechanical Parts**: Various structural components for assembling the robotic arm.

## Installation Steps
1. **Clone the Repository**:
   - Open your terminal or command prompt and run:
     ```bash
     git clone https://github.com/yourusername/robotic-arm.git
     cd robotic-arm
     ```

2. **Install Arduino IDE**:
   - Ensure the Arduino IDE is installed on your computer.

3. **Upload the Code**:
   - Open the `robotic_arm.ino` file in the Arduino IDE.
   - Upload the code to your Arduino UNO.

4. **Set Up the MIT App**:
   - Create a new project in MIT App Inventor.
   - Design the user interface with buttons for each control.
   - Program the buttons to send commands via Bluetooth as outlined below.

## Control Commands
Each button in the mobile app corresponds to a specific command for the robotic arm:
- **Base Rotation**:
  - **Clockwise**: Sends command `"1"`
  - **Counter-Clockwise**: Sends command `"2"`
- **Shoulder Movement**:
  - **Up**: Sends command `"3"`
  - **Down**: Sends command `"4"`
- **Elbow Movement**:
  - **Up**: Sends command `"5"`
  - **Down**: Sends command `"6"`
- **Wrist Rotation**:
  - **Clockwise**: Sends command `"7"`
  - **Counter-Clockwise**: Sends command `"8"`
- **Gripper Control**:
  - **Open**: Sends command `"9"`
  - **Close**: Sends command `"0"`
- **Reset**: Sends command `"R"` to reset all servo positions.

## Conclusion
This Bluetooth-Controlled Robotic Arm project serves as an engaging platform to learn about robotics, automation, and mobile app development. With the ability to control movements wirelessly, this project opens the door to a variety of applications, from educational tools to advanced automation solutions.

---

Thank you for exploring the Bluetooth-Controlled Robotic Arm project! Enjoy building and customizing your own robotic arm!
