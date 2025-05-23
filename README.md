# Zixi Li – Engineering Portfolio

Welcome! I'm a Mechatronics Engineering student at Texas A&M specializing in robotics, AI, and embedded systems.

---

## Projects

### Saffron Auto Harvester
- Led a multidisciplinary team to develop an autonomous robot capable of detecting, approaching, and extracting saffron stigmas from blossoms using real-time AI vision and a 6-degree-of-freedom (6-DOF) robotic arm.
- Programmed inverse kinematics (IK) algorithms in Python using the Jacobian matrix method to compute joint angles for a 6-DOF robotic arm, enabling sub-centimeter precision during stigma extraction.
- Integrated open-loop servo control with angle calibration and joint-limit safety checks to drive six PWM-controlled motors; optimized timing sequences to minimize jitter and lag during movement.
- Developed and trained a YOLOv4-tiny object detection model using Darknet framework on a dataset of 200,000+ labeled images, achieving 72.73% mAP in detecting saffron stigmas under variable lighting and occlusion conditions.
- Engineered a real-time distance estimation algorithm using the pinhole camera model and calibrated focal length, allowing for dynamic object tracking and chassis alignment based on bounding box dimensions.
- Implemented a state-machine-driven navigation and manipulation system, fusing Pi Camera input with Hailo AI accelerator inference and motor control logic to autonomously stop 30 cm from the blossom, align the arm, and perform extraction.
- Assembled custom mobile chassis using aluminum plates, DC motors, and tank tread system for high traction in agricultural terrain; designed gripper and arm mount to balance weight distribution.
- Designed and soldered a custom motor control board using L298N H-bridges and voltage regulators to interface high-power DC motors with Raspberry Pi GPIOs, enabling dual-direction control and PID tuning.
- Debugged system-wide integration errors between camera feed, YOLO inference, IK solver, and motor actuation using serial logging and step-through test scripts; achieved stable performance across 1-hour continuous operation.
- Managed project planning and procurement using WBS, Gantt charts, and a detailed Bill of Materials (BOM); coordinated 10+ material suppliers to keep costs within budget despite international shipping delays.
- Presented the system at the departmental design showcase with live demo of robotic stigma harvesting; received faculty recognition for innovation and cross-domain integration of AI and mechatronics.
![Saffron Harvester Robot Master Drawing](RedGold_MasterDrawing.png)

---

### Balloon Destroyer
- Selected by faculty for presentation at the department showcase for demonstrating advanced real-time targeting and autonomous robotics in a competitive classroom setting.
- Developed a full-stack control system in Python running on a Linux-based platform (Raspberry Pi), integrating image processing, motion control, and autonomous decision-making.
- Implemented color-based object tracking using OpenCV to identify and follow balloons of a specified hue in variable lighting environments.
- Engineered autonomous navigation logic with real-time obstacle detection using 2D Lidar data and proximity thresholds; robot rerouted dynamically to avoid collisions and reengage targets.
- Programmed conditional firing mechanism based on temporal stability detection—target engagement was triggered only after the balloon remained within the frame and stationary for ≥3 seconds.
- Achieved high targeting precision through real-time angle calculation between the camera center and object centroid, dynamically adjusting a servo-driven turret before firing.
- Designed and fabricated mechanical frame using aluminum and acrylic components; integrated motor drivers, ultrasonic sensors, and Li-ion power systems for mobile autonomy.
- Optimized control loop frequency and task prioritization, balancing sensor polling, motion control, and camera processing to minimize latency and improve responsiveness.
- Performed extensive field testing across varying indoor conditions to calibrate firing delay, improve object recognition under different backgrounds, and reduce false triggers.


Demo Video: [Watch here](https://drive.google.com/file/d/13DOgFnZRKw2B_BtkJqVHfoBgalWu6pOa/view)

---

### PID Controlled Line-Follower Robot
- Designed and fabricated a custom mobile chassis using precision-cut aluminum plates and mounted dual rear-drive DC motors for optimal weight distribution and stability.
- Developed closed-loop motor control logic using an Arduino Mega 2560 with finely tuned PID (Proportional–Integral–Derivative) parameters to ensure smooth and accurate turning across curves and junctions.
- Integrated a front-mounted tri-sensor infrared array to continuously detect floor-mounted tape lines; used sensor differentials to dynamically adjust motor speeds and maintain centerline alignment.
- Implemented real-time control loop for sensor polling, error calculation, and motor speed adjustments, achieving stable line-following performance even at variable speeds.
- Debugged system performance through serial monitoring and live tuning of PID constants; minimized oscillation and overshoot during high-speed cornering.
- Tested and validated robot behavior on multi-turning tracks to ensure robustness and consistency.

Demo Video: [Watch here](https://drive.google.com/file/d/1lq5InaX54CyKnYxklKG4WbiJVY_GtGbp/view)

---

## Skills
Python • C++ • Embedded Systems • Blender • ROS2 • HVAC • MATLAB
