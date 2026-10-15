

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=venom&height=300&color=0:080808,25:260606,60:8B0000,100:FF2020&text=RAVEN-X&fontColor=FFFFFF&fontSize=82&fontAlignY=45&animation=fadeIn&stroke=FF3030&strokeWidth=2"
    width="100%"
    alt="RAVEN-X Autonomous Robotics Project"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=2500&pause=700&color=FF3030&center=true&vCenter=true&width=950&height=80&lines=AUTONOMOUS+MOBILE+ROBOTICS;SELF-VERIFYING+%2F+SELF-DIAGNOSING;SELF-RECOVERING+CYBER-PHYSICAL+SYSTEMS;CROSS-LAYER+PHYSICAL+CONSISTENCY;DETECT.+DIAGNOSE.+RECOVER."
    alt="RAVEN-X System Capabilities"
  />
</p>

<p align="center">
  <strong>
    A SELF-VERIFYING, SELF-DIAGNOSING AND SELF-RECOVERING
    <br/>
    CYBER-PHYSICAL MOBILE ROBOT
  </strong>
</p>

<p align="center">
  <em>Using Cross-Layer Physical Consistency</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-RAVEN--X-FF3030?style=for-the-badge&labelColor=080808" alt="Project RAVEN-X"/>
  <img src="https://img.shields.io/badge/DOMAIN-AUTONOMOUS_ROBOTICS-FFFFFF?style=for-the-badge&labelColor=202020" alt="Autonomous Robotics"/>
  <img src="https://img.shields.io/badge/CORE-PHYSICAL_CONSISTENCY-B91C1C?style=for-the-badge&labelColor=080808" alt="Physical Consistency"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DETECT-ANOMALIES-FF3030?style=flat-square&labelColor=111111" alt="Anomaly Detection"/>
  <img src="https://img.shields.io/badge/DIAGNOSE-FAULTS-FF5555?style=flat-square&labelColor=111111" alt="Fault Diagnosis"/>
  <img src="https://img.shields.io/badge/RECOVER-BOUNDED_MODES-FFFFFF?style=flat-square&labelColor=8B0000" alt="Bounded Recovery"/>
</p>

<p align="center">
  <code>[ SENSOR INPUT ]</code>
  &nbsp;━━━&gt;&nbsp;
  <code>[ PHYSICAL CONSISTENCY ]</code>
  &nbsp;━━━&gt;&nbsp;
  <code>[ SAFE RESPONSE ]</code>
</p>

<p align="center">
  <strong>NOT JUST DETECTING FAILURE — REASONING ABOUT PHYSICAL REALITY.</strong>
</p>

---

<!-- ==================== PART I | PROJECT DEFINITION ==================== -->

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=25&duration=2200&pause=1000&color=FF3030&center=true&vCenter=true&width=650&height=45&lines=PART+I+%E2%80%94+PROJECT+DEFINITION" alt="Part I Project Definition"/>
</h1>

## <img src="https://img.shields.io/badge/01-PROJECT_DESCRIPTION-FF3030?style=for-the-badge&labelColor=111111" alt="Project Description"/>

RAVEN-X is a differential-drive autonomous mobile robot designed to investigate cross-layer fault detection, diagnosis, and bounded recovery in cyber-physical robotic systems.

The platform combines an embedded real-time controller, a high-level edge-computing system, multiple physical sensors, autonomous navigation software, and an anomaly-detection pipeline. Its defining feature is a Physical Consistency Engine (PCE) that evaluates whether measurements from different subsystems agree with the expected physical behavior of the robot.

A conventional mobile robot may detect an obstacle and stop. RAVEN-X additionally asks questions such as:

- Is the wheel encoder reporting motion when the robot body is not moving?
- Is a motor drawing excessive current while its wheel remains stationary?
- Is the IMU consistent with wheel odometry?
- Has a sensor stopped updating?
- Is the robot experiencing wheel slip, a sensor failure, or an actuator problem?
- Can the mission continue safely using a degraded operating mode?
- Is the evidence too uncertain to permit continued motion?

---

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=14&duration=35&pause=600&color=FF4545&center=false&vCenter=true&multiline=true&width=950&height=150&lines=%3E+MONITORING+PHYSICAL+BEHAVIOR...;%3E+COMPARING+CROSS-LAYER+EVIDENCE...;%3E+CHECKING+SENSOR-ACTUATOR+CONSISTENCY...;%3E+EVALUATING+FAULT+CONFIDENCE...;%3E+SELECTING+SAFE+OPERATING+MODE..."
    alt="RAVEN-X Physical Consistency Engine Console"
    width="100%"
  />
</p>

<p align="center">
  <sub>RAVEN-X — PHYSICAL CONSISTENCY • FAULT REASONING • BOUNDED RECOVERY</sub>
</p>
```




![image alt](https://github.com/BenkhiraAhmedBaderEddine1/RAVEN-X-Self-Verifying-Self-Healing-Cyber-Physical-Robot-/blob/813d275251a17ecf63a6f794ce841bbf03b5a8e6/10001212.png)





🛑  The platform uses two principal computing layers.

![image alt](https://github.com/BenkhiraAhmedBaderEddine1/RAVEN-X-Self-Verifying-Self-Healing-Cyber-Physical-Robot-/blob/813d275251a17ecf63a6f794ce841bbf03b5a8e6/photo_2026-10-15_01-37-17.jpg)

1.1 Research objectives

---

## <img src="https://img.shields.io/badge/01-RESEARCH_OBJECTIVES-EF4444?style=for-the-badge&labelColor=111111" alt="Research Objectives"/>

<details open>
<summary><strong>O1 — System Integration</strong></summary>

Build a differential-drive robot with wheel encoders, inertial sensing, motor-current monitoring, battery monitoring, and optional LiDAR and camera perception.

</details>

<details open>
<summary><strong>O2 — Physical Consistency</strong></summary>

Develop a method for comparing commanded motion with measured wheel motion and independent body-motion estimates.

</details>

<details open>
<summary><strong>O3 — Fault Detection</strong></summary>

Detect abnormal operating conditions using thresholds, residual analysis, statistical methods, and machine learning.

</details>

<details open>
<summary><strong>O4 — Fault Diagnosis</strong></summary>

Distinguish among sensor faults, actuator faults, wheel slip, communication failures, power anomalies, and unknown faults.

</details>

<details open>
<summary><strong>O5 — Bounded Recovery</strong></summary>

Implement safe responses such as speed reduction, sensor isolation, navigation degradation, controlled stop, and restart of selected non-safety software services.

</details>

<details open>
<summary><strong>O6 — Experimental Validation</strong></summary>

Compare the proposed system against threshold-only and machine-learning-only baselines using reproducible fault-injection experiments.

</details>

<details open>
<summary><strong>O7 — Research Reproducibility</strong></summary>

Publish the software architecture, configuration, experiment protocol, data schema, and evaluation methodology.

</details>
```

1.2 Research questions

---

## <img src="https://img.shields.io/badge/02-RESEARCH_QUESTIONS-DC2626?style=for-the-badge&labelColor=111111" alt="Research Questions"/>

| ID | Research Question |
|:--:|---|
| <img src="https://img.shields.io/badge/RQ1-EF4444?style=flat-square" alt="RQ1"/> | Does cross-layer physical consistency improve fault-detection performance compared with independent sensor thresholds? |
| <img src="https://img.shields.io/badge/RQ2-EF4444?style=flat-square" alt="RQ2"/> | Can independent sensor evidence distinguish wheel slip from encoder failure and motor stall? |
| <img src="https://img.shields.io/badge/RQ3-EF4444?style=flat-square" alt="RQ3"/> | What are the effects of sampling frequency, sensor synchronization, and communication delay on diagnosis? |
| <img src="https://img.shields.io/badge/RQ4-EF4444?style=flat-square" alt="RQ4"/> | Can bounded recovery improve mission completion without increasing unsafe behavior? |
| <img src="https://img.shields.io/badge/RQ5-EF4444?style=flat-square" alt="RQ5"/> | What computational and power overhead is introduced by the proposed diagnosis pipeline? |
| <img src="https://img.shields.io/badge/RQ6-EF4444?style=flat-square" alt="RQ6"/> | How well does the system generalize to faults and environments absent from its training data? |

```

```
‎1.3 Hypotheses
-

---

## <img src="https://img.shields.io/badge/03-RESEARCH_HYPOTHESES-B91C1C?style=for-the-badge&labelColor=111111" alt="Research Hypotheses"/>

> [!NOTE]
> These are research hypotheses, not established results. Each must be tested against a predefined baseline.

| Hypothesis | Expected research outcome |
|:--:|---|
| **H1** | Combining independent physical measurements will reduce some false alarms relative to single-sensor thresholding. |
| **H2** | A hybrid rule-based and statistical approach will offer more interpretable diagnosis than a classifier operating on isolated measurements. |
| **H3** | Recovery policies that explicitly account for uncertainty will improve operational robustness compared with unconditional recovery. |
| **H4** | Diagnosis performance will deteriorate when multiple faults occur simultaneously or when the reference sensors share correlated errors. |

```

```

und the public, guaranteed fault isolation, or immunity to cyberattacks. Those would require additional engineering and evidence.

---


5. Introduction

## <img src="https://img.shields.io/badge/04-INTRODUCTION-EF4444?style=for-the-badge&labelColor=111111" alt="Introduction"/>

Autonomous mobile robots integrate mechanical, electrical, computational, and software components within a single cyber-physical system. Their reliability depends not only on the correctness of individual components but also on the consistency of information exchanged between them.

A wheel encoder, for example, measures wheel rotation rather than the absolute motion of the robot body. Under normal traction, wheel rotation can provide a useful estimate of linear displacement. During wheel slip, however, the wheel may rotate without producing the expected body movement. An odometry algorithm that relies exclusively on encoder measurements may consequently produce an incorrect estimate of the robot's position.

A similar ambiguity occurs when a robot slows down unexpectedly. Possible explanations include excessive mechanical load, motor failure, battery-voltage sag, encoder malfunction, communication delay, or an environmental disturbance. A simple current threshold may detect unusual behavior, but it may not determine the underlying cause.

This thesis proposes RAVEN-X, a mobile robotic research platform designed to investigate these problems through cross-layer physical consistency. The system evaluates relationships between commanded velocities, wheel encoder measurements, inertial observations, electrical power, communication health, and optional LiDAR-based motion estimates.

The architecture combines a high-level edge-computing system running ROS 2 with a real-time embedded motor controller. The high-level system performs navigation, logging, anomaly analysis, and diagnosis. The embedded controller executes bounded motor commands and maintains local safety constraints independently of the high-level autonomy stack.

The project follows a staged experimental methodology. Initially, the platform is characterized under healthy operating conditions. Controlled faults are then introduced, one at a time, followed by selected combinations of faults. The resulting measurements are used to calibrate thresholds, evaluate diagnosis methods, and quantify recovery performance.

The research contribution is the specific architecture, implementation, and evaluation of cross-layer consistency and bounded recovery on a low-cost mobile robot. The project does not assume that individual techniques such as sensor fusion, anomaly detection, or runtime monitoring are new. Its novelty must be established through a systematic literature review and a comparison with prior work.

---

6. Abstract and keywords

   
## <img src="https://img.shields.io/badge/05-ABSTRACT-DC2626?style=for-the-badge&labelColor=111111" alt="Abstract"/>

RAVEN-X is a research platform for cross-layer fault detection, diagnosis, and bounded recovery in autonomous mobile robots. The system combines a differential-drive mechanical platform, an embedded motor controller, a high-level edge computer, and a heterogeneous sensor suite. Its central component, the Physical Consistency Engine, compares commanded motion with encoder-derived velocity, inertial measurements, electrical current, battery state, communication health, and optional exteroceptive motion estimates.

The proposed architecture uses deterministic embedded control for motor regulation and safety enforcement, while a ROS 2-based high-level system performs sensor integration, anomaly analysis, navigation, and event logging. Fault detection begins with calibrated thresholds and normalized residuals. Statistical and machine-learning methods are added only after a representative dataset has been collected. A diagnosis manager estimates likely fault classes and associates each decision with supporting evidence and an uncertainty level.

A bounded recovery manager selects among normal operation, speed-limited operation, reduced-sensor operation, controlled stop, and operator intervention. Safety-critical functions remain independent of the machine-learning pipeline. Experimental evaluation uses controlled fault injection and compares threshold-only, machine-learning-only, and proposed hybrid approaches.

The evaluation metrics include detection latency, false-alarm rate, precision, recall, F1-score, diagnosis accuracy, recovery success, mission completion, and computational overhead. The intended outcome is a reproducible research platform for investigating the relationship between physical consistency, fault diagnosis, and safe recovery in embedded autonomous robotics.

**Keywords:** Cyber-physical systems, mobile robotics, ROS 2, STM32, edge AI, anomaly detection, fault diagnosis, sensor fusion, runtime safety, fault-tolerant control.


7. Project scope and limitations

## <img src="https://img.shields.io/badge/06-PROJECT_SCOPE_AND_LIMITATIONS-B91C1C?style=for-the-badge&labelColor=111111" alt="Project Scope and Limitations"/>

The first implementation targets indoor, low-speed, differential-drive operation on a controlled laboratory floor.

### <img src="https://img.shields.io/badge/INCLUDED-INITIAL_SCOPE-16A34A?style=flat-square" alt="Included Initial Scope"/>

- Low-level wheel-speed control.
- Encoder, IMU, current, and battery telemetry.
- A communication bridge between the embedded controller and Jetson.
- Physical-consistency calculations.
- Threshold-based anomaly detection.
- Event logging and dataset generation.
- Controlled recovery and safe-stop states.
- Reproducible fault-injection experiments.

### <img src="https://img.shields.io/badge/OPTIONAL-ADVANCED_FEATURES-0EA5E9?style=flat-square" alt="Optional Advanced Features"/>

- LiDAR-based SLAM and autonomous navigation.
- RGB-D perception.
- GPU-accelerated inference.
- Temporal neural networks.
- Digital-twin-based parameter estimation.
- Causal diagnosis and multi-robot cooperation.

### <img src="https://img.shields.io/badge/IMPORTANT-RESEARCH_LIMITATIONS-F59E0B?style=flat-square" alt="Research Limitations"/>

The project does not initially claim certification for industrial safety, autonomous operation around the public, guaranteed fault isolation, or immunity to cyberattacks. Those would require additional engineering and evidence.



```mermaid
flowchart TB

    subgraph ROBOT["01 - PHYSICAL ROBOT"]
        S["SENSORS AND PHYSICAL SYSTEM<br/>Wheel Encoders | IMU | Motor Current<br/>Battery Voltage | Optional LiDAR / Camera"]
    end

    subgraph MCU["02 - REAL-TIME SAFETY LAYER"]
        M["STM32 EMBEDDED CONTROLLER<br/>Encoder Capture | PID | PWM<br/>Command Validation | Watchdog<br/>Low-Level Motor Safety Limits"]
    end

    L["UART / CAN COMMUNICATION<br/>Message Validation | Timeouts | Link Health"]

    subgraph EDGE["03 - HIGH-LEVEL INTELLIGENCE"]
        J["JETSON EDGE COMPUTER - ROS 2<br/>Sensor Fusion | Logging | AI | Navigation"]
        P["PHYSICAL CONSISTENCY ENGINE<br/>Compare Commands, Wheel Motion,<br/>IMU, Current and Independent Evidence"]
        D["FAULT DIAGNOSIS<br/>Sensor | Actuator | Wheel Slip<br/>Communication | Power | Unknown Fault"]

        J --> P
        P --> D
    end

    subgraph REC["04 - BOUNDED RECOVERY"]
        R{"RECOVERY DECISION"}
        N["NORMAL OPERATION"]
        G["DEGRADED MODE<br/>Speed Limit | Reduced Functionality"]
        T["CONTROLLED STOP"]
        F["LATCHED FAULT<br/>Operator Inspection / Reset"]

        R --> N
        R --> G
        R --> T
        R --> F
    end

    S --> M
    M <--> L
    L <--> J
    D --> R

    N -.-> J
    G -.-> J
    T -.-> M
    F -.-> M

    classDef sensors fill:#102A43,stroke:#38BDF8,color:#FFFFFF
    classDef embedded fill:#17212E,stroke:#94A3B8,color:#FFFFFF
    classDef comm fill:#20202A,stroke:#A78BFA,color:#FFFFFF
    classDef edge fill:#12372F,stroke:#2DD4BF,color:#FFFFFF
    classDef engine fill:#153B35,stroke:#5EEAD4,color:#FFFFFF
    classDef decision fill:#241419,stroke:#F87171,color:#FFFFFF
    classDef safe fill:#123323,stroke:#4ADE80,color:#FFFFFF
    classDef degraded fill:#3A2A10,stroke:#FBBF24,color:#FFFFFF
    classDef stop fill:#451414,stroke:#F87171,color:#FFFFFF
    classDef fault fill:#290D14,stroke:#FB7185,color:#FFFFFF

    class S sensors
    class M embedded
    class L comm
    class J edge
    class P,D engine
    class R decision
    class N safe
    class G degraded
    class T stop
    class F fault

    style ROBOT fill:#0B1420,stroke:#38BDF8,stroke-width:2px
    style MCU fill:#10151E,stroke:#94A3B8,stroke-width:2px
    style EDGE fill:#0B1917,stroke:#2DD4BF,stroke-width:2px
    style REC fill:#180D12,stroke:#EF4444,stroke-width:2px

    linkStyle default stroke:#EF4444,stroke-width:2px
```

1. Hardware components — professional comparison table

```markdown
---

## <img src="https://img.shields.io/badge/06-HARDWARE_COMPONENTS-EF4444?style=for-the-badge&labelColor=111111" alt="Hardware Components and Their Functions"/>

> [!IMPORTANT]
> The diagram is a logical architecture, not a complete electrical schematic. In particular, the emergency-stop circuit must act on the motor-energy path independently of ROS 2 and the Jetson.

The following bill of materials is a proposed configuration. Exact part numbers, voltage ratings, motor stall current, connector pinouts, and availability must be checked before purchasing.

### <img src="https://img.shields.io/badge/COMPONENTS-HARDWARE_OVERVIEW-DC2626?style=flat-square&labelColor=111111" alt="Hardware Overview"/>

| Component | Function in RAVEN-X | Advantages | Limitations |
|---|---|---|---|
| **NVIDIA Jetson Orin Nano Super 8GB** | High-level computation and optional edge AI | GPU acceleration, Linux, ROS 2, camera processing | Power, heat, software complexity, 8 GB shared memory |
| **STM32H743 development board** | Embedded control and local safety | Timers, encoder interfaces, ADC, fast control loop | Firmware integration and peripheral mapping required |
| **Two geared DC motors with quadrature encoders** | Differential-drive locomotion and feedback | Speed measurement, closed-loop control | Backlash, slip, encoder errors, mechanical wear |
| **Dual-channel motor driver** | Supplies motor power from battery | Hardware PWM/DIR interface | Current and thermal limits; stall current must be considered |
| **9-axis IMU** | Angular velocity and acceleration measurements | Independent motion evidence | Bias, vibration, drift, calibration errors |
| **Two current/voltage monitors** | Motor electrical telemetry | Load and stall evidence | Requires correct shunt design and wiring |
| **Battery monitor/BMS** | Power-state monitoring and battery protection | Helps detect voltage sag and battery faults | Does not replace correctly rated fuses or a safety circuit |
| **2D LiDAR, optional for Phase 1** | Mapping and external motion evidence | Useful for SLAM and obstacle detection | Cost, driver integration, reflective or transparent surfaces |
| **RGB-D/stereo camera, optional** | Visual perception and object detection | Enables vision-based extensions | Lighting sensitivity, bandwidth, compute demand |
| **Emergency-stop switch and power disconnect** | Independent motor-energy isolation | Hardware-level stopping path | Must be designed and verified for the selected electrical system |
| **DC/DC converters** | Separate regulated logic and computing rails | Cleaner power distribution | Thermal dissipation, transient response, grounding |
| **Chassis, wheels, brackets** | Mechanical support | Modular prototyping | Alignment and vibration affect measurements |
| **Fuse, wiring, connectors, mounting hardware** | Electrical and mechanical integration | Serviceability and protection | Incorrect ratings can create hazards |

### <img src="https://img.shields.io/badge/COMPUTING_PLATFORM-JETSON_ORIN_NANO-16A34A?style=flat-square&labelColor=111111" alt="Jetson Platform"/>

The Jetson Orin Nano Super Developer Kit offers four USB 3.2 Type-A ports, a 40-pin expansion header, camera connectors, and an M.2 slot. Those interfaces are useful for prototyping, but the carrier-board specification must be consulted for electrical pin assignments and limits.

### <img src="https://img.shields.io/badge/EMBEDDED_PLATFORM-STM32H743-0EA5E9?style=flat-square&labelColor=111111" alt="STM32 Platform"/>

The STM32H743 offers multiple communication and control peripherals, but the exact timer channels and pins depend on the specific development board and its pin mapping.

---
```
2. Recommended build sequence

```markdown
## <img src="https://img.shields.io/badge/06.1-RECOMMENDED_BUILD_SEQUENCE-EF4444?style=for-the-badge&labelColor=111111" alt="Recommended Build Sequence"/>

The development process is divided into three phases. Each phase establishes a stable foundation for the next.

### <img src="https://img.shields.io/badge/PROTOTYPE_A-MINIMUM_RESEARCH_PLATFORM-16A34A?style=for-the-badge&labelColor=111111" alt="Prototype A"/>

**Objective:** Establish reliable motor control, sensor acquisition, and independent hardware safety.

- [ ] Chassis and two motors.
- [ ] Motor driver.
- [ ] STM32 board.
- [ ] Wheel encoders.
- [ ] IMU.
- [ ] Current monitoring.
- [ ] Battery-voltage monitoring.
- [ ] Emergency stop.
- [ ] USB-UART communication.

**Exit criterion:** Verify motor control, telemetry, watchdog behavior, command limits, and the independent emergency-stop path before adding high-level autonomy.

---

### <img src="https://img.shields.io/badge/PROTOTYPE_B-INTEGRATED_AUTONOMY-0EA5E9?style=for-the-badge&labelColor=111111" alt="Prototype B"/>

**Objective:** Integrate high-level computation and autonomous navigation.

- [ ] Add the Jetson.
- [ ] Configure ROS 2 communication.
- [ ] Integrate LiDAR.
- [ ] Implement mapping and localization.
- [ ] Add navigation.
- [ ] Connect sensor telemetry to the Physical Consistency Engine.

**Exit criterion:** Validate end-to-end communication, timestamp handling, sensor synchronization, and safe behavior when high-level software becomes unavailable.

---

### <img src="https://img.shields.io/badge/PROTOTYPE_C-ADVANCED_RESEARCH-B91C1C?style=for-the-badge&labelColor=111111" alt="Prototype C"/>

**Objective:** Extend the platform with advanced diagnosis and recovery research.

- [ ] Add a camera.
- [ ] Optimize AI inference.
- [ ] Develop temporal diagnosis.
- [ ] Evaluate advanced recovery policies.
- [ ] Run reproducible fault-injection experiments.
- [ ] Compare methods against predefined baselines.

**Exit criterion:** Report detection performance, diagnosis accuracy, recovery outcomes, uncertainty, and computational overhead.

---

> [!TIP]
> This order reduces integration risk: motor control and hardware safety are verified before the project becomes dependent on Linux, navigation, or AI.

---
```
