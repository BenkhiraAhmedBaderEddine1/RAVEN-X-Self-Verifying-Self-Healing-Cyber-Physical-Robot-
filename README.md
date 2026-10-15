```html
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=260&color=0:08090C,35:171B22,70:7F1D1D,100:EF4444&text=RAVEN-X&fontColor=FFFFFF&fontSize=64&fontAlignY=40&animation=fadeIn&stroke=EF4444&strokeWidth=2" width="100%" alt="RAVEN-X Robotics Banner"/>
</p>

<p align="center">
  <strong>
    A Self-Verifying, Self-Diagnosing and Self-Recovering
    <br/>
    Cyber-Physical Mobile Robot
  </strong>
  <br/>
  <sub>Using Cross-Layer Physical Consistency</sub>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=15&duration=2600&pause=900&color=EF4444&center=true&vCenter=true&width=900&height=70&lines=AUTONOMOUS+ROBOTICS+%7C+SYSTEM+INTEGRITY;SELF-VERIFICATION+%7C+SELF-DIAGNOSIS;FAULT+DETECTION+%7C+SELF-RECOVERY;CROSS-LAYER+PHYSICAL+CONSISTENCY" alt="RAVEN-X Animated Robotics Tagline"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DOMAIN-CYBER--PHYSICAL_ROBOTICS-EF4444?style=for-the-badge&labelColor=08090C" alt="Cyber-Physical Robotics"/>
  <img src="https://img.shields.io/badge/CORE-SELF--DIAGNOSIS-FFFFFF?style=for-the-badge&labelColor=171B22" alt="Self-Diagnosis"/>
  <img src="https://img.shields.io/badge/APPROACH-CROSS--LAYER_CONSISTENCY-B91C1C?style=for-the-badge&labelColor=08090C" alt="Cross-Layer Consistency"/>
</p>

<p align="center">
  <code>VERIFY THE STATE.</code>
  &nbsp;|&nbsp;
  <code>DIAGNOSE THE FAULT.</code>
  &nbsp;|&nbsp;
  <code>RECOVER WITH PURPOSE.</code>
</p>

---
```
‎  RAVEN-X is an autonomous cyber-physical mobile robot designed to investigate intelligent fault detection, diagnosis, recovery and safety in embedded robotic systems. Unlike a conventional autonomous mobile robot that focuses primarily on navigation and obstacle avoidance, RAVEN-X continuously evaluates the consistency between high-level commands, actuator behavior, wheel encoder measurements, inertial motion, electrical power, communication health and environmental perception.

The central idea is to create a robot that does not simply execute commands, but also verifies whether the physical behavior of the robot is coherent with the expected behavior. When an inconsistency is detected, the system attempts to determine whether the cause is a sensor fault, actuator fault, mechanical disturbance, environmental change, communication anomaly, computing problem or a combination of faults.

The architecture combines a high-level NVIDIA Jetson computer running ROS 2 with an STM32H743 real-time embedded controller. The Jetson is responsible for autonomous navigation, perception, SLAM, data logging, anomaly analysis, machine-learning inference and high-level decision making. The STM32 is responsible for deterministic motor control, encoder processing, PID regulation, safety supervision, watchdog handling, hardware limits and emergency-stop logic.

RAVEN-X introduces a cross-layer Physical Consistency Engine in which independent measurements are compared against physical and kinematic expectations. For example, a commanded wheel velocity is compared with encoder velocity, inertial motion and motor current. Such cross-layer evidence can help distinguish between a motor fault and environmental wheel slip, or between an encoder failure and a genuine loss of motion.

The robot is organized around the operational sequence:

Sense → Synchronize → Verify → Diagnose → Decide → Isolate → Adapt → Recover/Stop → Log.

The project is therefore not limited to robotics. It combines embedded systems, real-time control, mobile robotics, sensor fusion, cybersecurity, anomaly detection, machine learning, fault tolerance, system monitoring and experimental science.

The principal research contribution is not the general idea of an autonomous robot, which is already well established. Rather, the contribution is the implementation and experimental evaluation of a specific cross-layer physical-consistency architecture and bounded recovery strategy on a low-cost differential-drive embedded robot. The system is intended to produce reproducible telemetry, controlled fault-injection experiments and quantitative evidence concerning detection latency, diagnosis accuracy, false-alarm rate, recovery success, mission completion and computational overhead.


The platform is also designed as a foundation for future research in edge AI, causal diagnosis, digital-twin-based system identification, adaptive autonomy, formal runtime verification and cooperative multi-robot fault diagnosis.


═════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════
 
𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃                                                                                                                         𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃
𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃                                                            INTRODUCTION                                                 𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃
𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃                                                                                                                         𝄃𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃
═════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════

═════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════


Autonomous mobile robots integrate sensing, actuation, computation, communication and physical interaction within a single cyber-physical system. A failure in one subsystem can propagate across multiple layers and may be difficult to distinguish from an environmental disturbance or cyber anomaly. RAVEN-X proposes a self-verifying, self-diagnosing and self-healing mobile robot architecture based on cross-layer physical consistency.

The proposed platform combines an NVIDIA Jetson high-level computer running ROS 2 with an STM32H743 real-time controller. The robot integrates wheel encoders, inertial sensing, motor-current monitoring, battery monitoring, 2D LiDAR and optional RGB-D perception. A Physical Consistency Engine compares commanded behavior with measured actuator response, inertial motion, electrical state and communication health. Statistical and machine-learning models generate anomaly scores, while a diagnosis layer classifies abnormal conditions and a bounded recovery manager selects degraded operation, sensor isolation, recovery or safe stop.
   
The system is evaluated through controlled fault-injection experiments covering sensor failures, actuator disturbances, wheel slip, power degradation and communication anomalies. Evaluation metrics include detection latency, false-alarm rate, precision, recall, F1-score, diagnosis accuracy, recovery success rate, mission completion rate and computational overhead.

The main contribution is an implemented and experimentally evaluated cross-layer physical-consistency architecture for a low-cost embedded differential-drive robot. The architecture is designed to support future research in edge artificial intelligence, causal diagnosis, digital-twin-based system identification, formal runtime safety verification and multi-robot cooperative diagnosis.
