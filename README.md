# Line-Following-Robot
Developed an autonomous line-following robot using Arduino, C++, and Fusion 360.
## 📌 Project Overview  
This project involves the **design, construction and development of an autonomous line-following robot**, built by a high school team as part of a robotics curriculum. The robot, was developed using **Arduino**, C++ programming, and Fusion 360 for structural design. The objective was to **create a self-navigating robot that follows a black line and avoids obstacles**.

## 🎯 Objectives  
- Design and assemble a functional **line-following robot**.  
- Develop and integrate **Arduino-based programming** for motor and sensor control.  
- Troubleshoot and optimize **sensor and motor performance**.  
- Implement **obstacle detection and avoidance** features.  
## 🛠 Technologies Used  
- **Arduino Nano** for microcontroller operations.  
- **Fusion 360** for 3D modeling and base design.  
- **C++ and Arduino IDE** for programming logic.  
- **HC-SR04 Ultrasonic Sensor** for obstacle detection.  
- **TCRT5000L Infrared Sensors** for line-following capability.  
- **L298N Motor Driver** for motor control.  
- **3D-printed chassis** for structural support.  

## 📜 Project Development  
### 📅 Timeline and Key Milestones  
- **Initial Research & Planning:** Team assigned roles and defined project goals.  
- **Hardware Assembly:** Designed and printed the chassis, integrated motors and sensors.  
- **Software Development:** Coded the movement logic, including line-following and obstacle avoidance.  
- **Testing & Debugging:** Iteratively refined sensor positioning and motor responses.  
- **Final Adjustments:** Optimized sensor readings and completed the final assembly.  

### 🏗 Team Members & Roles  
- **Guillermo Sánchez:** Project coordinator & lead programmer.  
- **Fernando Espino:** Quality control & objectives manager.  
- **Fernando Pérez:** Team spokesperson & assistant coordinator.  
- **Juan Rodriguez:** Secretary & documentation manager.  

## ⚙️ How It Works  
1. The robot moves forward while continuously scanning the surface with **TCRT5000L sensors**.  
2. When it detects a black line, it adjusts wheel speeds to stay on track.  
3. If an obstacle is detected using **HC-SR04 ultrasonic sensors**, the robot **stops, navigates around it, and then returns to the line**.  
4. The **L298N motor driver** controls the movement based on sensor input.  
5. The process runs in a continuous **loop**, making real-time adjustments.  

## 🔬 Challenges & Solutions  
### ⚠️ Challenges Faced  
- **Sensor misalignment:** Initially, the robot had difficulty distinguishing the black line from the floor color.  
- **Wheel imbalance:** One wheel had inconsistent movement, causing deviations.  
- **Obstacle avoidance logic:** The robot struggled to realign after bypassing an obstacle.  

### ✅ Solutions Implemented  
- **Repositioned sensors** to be closer to the surface.  
- **Adjusted PWM values** to balance wheel rotation speeds.  
- **Refined obstacle detection logic** to improve accuracy.

## 📜 License  
This project is open-source and available under the **MIT License**. Feel free to modify and improve upon our work!  
