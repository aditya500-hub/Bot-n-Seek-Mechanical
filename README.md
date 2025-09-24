# Bot-n-Seek-Mechanical
Interactive multiplayer robotics game ; mechanical design, kinematics, FEA &amp; system integration
Bot ’n Seek – Multiplayer Robotics Game

Bot ’n Seek is an interactive robotics project where two bot rovers compete in a maze arena — one is the **Seeker** (with a laser tag mechanism) and the other is the **Hider** (equipped with light sensors to detect hits).  
This project demonstrates **mechanical design, kinematic modeling, FEA validation, and mechatronic integration**.

Objectives
- Design and fabricate robust **4WD chassis** for seeker and hider bots.
- Integrate **mechanical systems** (drivetrain, chassis, arena) with electronics (ESP32, RF modules, sensors).
- Validate mechanical performance via **FEA** and kinematic analysis.
- Deploy in a **public interactive event** with continuous player participation.

Mechanical Engineering Aspects
- **CAD Modeling (SolidWorks)**  
  - Optimized chassis with provisions for electronics mounting.  
  - Modular arena layout for reconfigurable maze design.  

Structural Analysis (FEA)
  - Load cases: impacts, vibration from motors.  
  - Material selection: ABS/Aluminum composite for stiffness & low weight.  

System Integration
- **Seeker:** Laser module + servo aiming system.  
- **Hider:** LDR sensor array for hit detection.  
- **Controller:** Joystick module with NRF24L01 wireless link.  
- **Feedback:** LEDs + buzzer.  

Arena
- Dimensions: 2m × 2m modular maze.  
- Obstacles, dead ends, and safe zones.  
- CAD layout: [Arena CAD]

Media
![Prototype](media/prototype_photo1.jpg)  
![Arena](media/arena_play.jpg)  

Future Scope
- Vision-based seeker (camera + OpenCV).  
- Autonomous navigation using SLAM.  
- Leaderboard and scoring system.  

License
This project is released under the [MIT License](LICENSE).
