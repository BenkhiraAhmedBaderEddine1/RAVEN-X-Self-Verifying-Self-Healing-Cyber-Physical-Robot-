 

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

![image alt](https://github.com/BenkhiraAhmedBaderEddine1/RAVEN-X-Self-Verifying-Self-Healing-Cyber-Physical-Robot-/blob/fcae59572a3a19521c270564fb0368f61a374361/photo_2026-10-15_04-06-51.jpg)

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



flowchart TD


## Robot Intelligence, Safety and Recovery Architecture

```mermaid
flowchart TD
    subgraph ROBOT["01 - PHYSICAL ROBOT"]
        S["SENSORS AND PHYSICAL SYSTEM<br/>Encoders | IMU | Motor Current<br/>Battery Voltage | Optional LiDAR / Camera"]
    end

    subgraph MCU["02 - EMBEDDED SAFETY"]
        M["STM32 CONTROLLER<br/>Encoder Capture | PID | PWM<br/>Command Validation | Watchdog<br/>Motor Safety Limits"]
    end

    L["UART / CAN COMMUNICATION<br/>Message Validation | Timeouts"]

    subgraph EDGE["03 - EDGE INTELLIGENCE"]
        J["JETSON AND ROS 2<br/>Sensor Fusion | Logging | Navigation"]
        P["PHYSICAL CONSISTENCY ENGINE<br/>Compare Commands and Sensor Evidence"]
        D["FAULT DIAGNOSIS<br/>Sensor | Actuator | Slip | Power | Communication"]

        J --> P
        P --> D
    end

    subgraph REC["04 - BOUNDED RECOVERY"]
        R{"RECOVERY DECISION"}
        N["NORMAL OPERATION"]
        G["DEGRADED MODE"]
        T["CONTROLLED STOP"]
        F["LATCHED FAULT"]

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

    classDef sensors fill:#102A43,stroke:#38BDF8,color:#FFFFFF,stroke-width:2px
    classDef embedded fill:#17212E,stroke:#94A3B8,color:#FFFFFF,stroke-width:2px
    classDef comm fill:#20202A,stroke:#A78BFA,color:#FFFFFF,stroke-width:2px
    classDef edge fill:#12372F,stroke:#2DD4BF,color:#FFFFFF,stroke-width:2px
    classDef engine fill:#153B35,stroke:#5EEAD4,color:#FFFFFF,stroke-width:2px
    classDef decision fill:#241419,stroke:#F87171,color:#FFFFFF,stroke-width:2px
    classDef safe fill:#123323,stroke:#4ADE80,color:#FFFFFF,stroke-width:2px
    classDef degraded fill:#3A2A10,stroke:#FBBF24,color:#FFFFFF,stroke-width:2px
    classDef stop fill:#451414,stroke:#F87171,color:#FFFFFF,stroke-width:2px
    classDef fault fill:#450A0A,stroke:#EF4444,color:#FFFFFF,stroke-width:3px

    class S sensors
    class M embedded
    class L comm
    class J edge
    class P engine
    class D decision
    class R decision
    class N safe
    class G degraded
    class T stop
    class F fault

    style ROBOT fill:#0B1220,stroke:#38BDF8,stroke-width:2px,color:#FFFFFF
    style MCU fill:#0B1220,stroke:#94A3B8,stroke-width:2px,color:#FFFFFF
    style EDGE fill:#0B1220,stroke:#2DD4BF,stroke-width:2px,color:#FFFFFF
    style REC fill:#0B1220,stroke:#F87171,stroke-width:2px,color:#FFFFFF
```

1. Hardware components — professional comparison table



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


2. Recommended build sequence

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

7. Mechanical Design
   ```markdown
---

## <img src="https://img.shields.io/badge/07-MECHANICAL_DESIGN-EF4444?style=for-the-badge&labelColor=111111" alt="Mechanical Design"/>

The platform uses a differential-drive configuration with two powered wheels and either a caster or an equivalent support mechanism.

### <img src="https://img.shields.io/badge/DESIGN_PARAMETERS-ENGINEERING_REFERENCE-64748B?style=flat-square&labelColor=111111" alt="Design Parameters"/>

| Parameter | Description | Unit |
|:---:|---|:---:|
| \(r\) | Effective wheel radius | m |
| \(L\) | Distance between left and right wheel contact centres | m |
| \(N\) | Encoder counts per motor revolution after accounting for quadrature decoding and gearbox ratio | counts/rev |
| \(G\) | Gearbox ratio, if the encoder is mounted on the motor shaft | ratio |
| \(m\) | Robot mass | kg |
| \(v_{\max}\) | Permitted linear speed | m/s |
| \(\omega_{\max}\) | Permitted angular speed | rad/s |

> [!IMPORTANT]
> The effective wheel radius should be measured under the actual robot load. Nominal wheel dimensions are not always sufficient because tire deformation and floor contact affect odometry.

### <img src="https://img.shields.io/badge/DIFFERENTIAL_DRIVE-KINEMATIC_MODEL-DC2626?style=flat-square&labelColor=111111" alt="Differential Drive Kinematics"/>

For a differential-drive robot:

**Linear velocity**

$$
v = \frac{r}{2}(\omega_R+\omega_L)
$$

**Angular velocity**

$$
\omega_z = \frac{r}{L}(\omega_R-\omega_L)
$$

where \(v\) is the estimated linear velocity and \(\omega_z\) is the angular velocity.

Conversely, the target wheel angular velocities are:

**Right wheel**

$$
\omega_R = \frac{v+\frac{L}{2}\omega_z}{r}
$$

**Left wheel**

$$
\omega_L = \frac{v-\frac{L}{2}\omega_z}{r}
$$

The equations provide wheel-speed targets for the embedded controller. They assume a planar differential-drive model and can become inaccurate during slip or significant wheel-ground interaction.

### <img src="https://img.shields.io/badge/CONTROL_PIPELINE-REFERENCE_FLOW-EF4444?style=flat-square&labelColor=111111" alt="Control Pipeline"/>

```text
VELOCITY TARGET
      |
      v
LINEAR / ANGULAR VELOCITY
      |
      v
DIFFERENTIAL-DRIVE KINEMATICS
      |
      v
LEFT AND RIGHT WHEEL TARGETS
      |
      v
EMBEDDED PID CONTROLLERS
      |
      v
MOTOR DRIVER
      |
      v
ENCODER FEEDBACK
```


8. Electrical Architecture and Wiring

8.1 Power distribution


## <img src="https://img.shields.io/badge/08-ELECTRICAL_ARCHITECTURE-EF4444?style=for-the-badge&labelColor=111111" alt="Electrical Architecture"/>

### <img src="https://img.shields.io/badge/08.1-POWER_DISTRIBUTION-DC2626?style=flat-square&labelColor=111111" alt="Power Distribution"/>

The following diagram represents functional power distribution, not a complete electrical schematic.


flowchart TB


```mermaid
flowchart TB
    B["BATTERY PACK"]
    F["MAIN FUSE"]
    E["HARDWARE MOTOR-ENERGY DISCONNECT"]
    P["MOTOR POWER BUS"]
    D["MOTOR DRIVER"]
    LM["LEFT MOTOR"]
    RM["RIGHT MOTOR"]

    DC["REGULATED DC/DC CONVERTERS"]
    J["JETSON INPUT RAIL"]
    S["STM32 SUPPLY"]
    I["IMU AND SENSOR SUPPLY"]
    C["CURRENT / VOLTAGE MONITORS"]

    B --> F
    F --> E
    E --> P
    P --> D
    D --> LM
    D --> RM

    B --> DC
    DC --> J
    DC --> S
    DC --> I
    DC --> C

    classDef battery fill:#20202A,stroke:#F87171,color:#FFFFFF,stroke-width:2px
    classDef protection fill:#451414,stroke:#EF4444,color:#FFFFFF,stroke-width:2px
    classDef power fill:#17212E,stroke:#94A3B8,color:#FFFFFF,stroke-width:2px
    classDef motor fill:#102A43,stroke:#38BDF8,color:#FFFFFF,stroke-width:2px
    classDef converter fill:#12372F,stroke:#2DD4BF,color:#FFFFFF,stroke-width:2px
    classDef electronics fill:#153B35,stroke:#5EEAD4,color:#FFFFFF,stroke-width:2px

    class B battery
    class F,E protection
    class P,D power
    class LM,RM motor
    class DC converter
    class J,S,I,C electronics

    linkStyle default stroke:#94A3B8,stroke-width:2px
```


> [!CAUTION]
> This is a functional diagram, not a wiring schematic with final ratings. A real build must use the battery, converter, and motor-driver manufacturer's electrical specifications to size the fuse, wire gauge, connectors, and thermal design.

The emergency-stop control must interrupt the motor-energy path using appropriately rated hardware. A software stop command is useful but is not a substitute for an independent hardware stop mechanism.

- Do not connect a motor directly to a microcontroller GPIO.
- Do not power the Jetson from an unregulated motor rail.
- Confirm logic-level compatibility before connecting UART, I²C, SPI, or GPIO signals.



8.2 Signal connections


### <img src="https://img.shields.io/badge/08.2-SIGNAL_CONNECTIONS-DC2626?style=flat-square&labelColor=111111" alt="Signal Connections"/>

| Signal | Source | Destination | Purpose |
|---|---|---|---|
| Left encoder A/B | Left motor encoder | STM32 timer inputs | Wheel speed and direction |
| Right encoder A/B | Right motor encoder | STM32 timer inputs | Wheel speed and direction |
| Left PWM/DIR | STM32 timer/GPIO | Motor driver | Left motor command |
| Right PWM/DIR | STM32 timer/GPIO | Motor driver | Right motor command |
| IMU I²C/SPI | IMU | STM32 or Jetson | Inertial measurements |
| Current monitor bus | Current monitor | STM32 or Jetson | Electrical load measurement |
| Battery voltage | Divider/monitor | Protected ADC/monitor | Battery telemetry |
| UART TX/RX | STM32 | Jetson USB-UART | Command and telemetry |
| Hardware E-stop | Physical switch | Rated motor-energy disconnect | Independent motor stop |
| LiDAR USB/UART | LiDAR | Jetson | Range measurements |
| Camera USB/CSI | Camera | Jetson | Image and optional depth data |

> [!NOTE]
> The table identifies signal functions, not universal pin numbers. Final pins must be selected after choosing the exact STM32 board, motor driver, sensor modules, and Jetson carrier board.


8.3 Wiring and electrical verification

### <img src="https://img.shields.io/badge/08.3-ELECTRICAL_VERIFICATION-EF4444?style=flat-square&labelColor=111111" alt="Electrical Verification"/>

Complete the following checks in sequence before normal operation.

- [ ] **01 — Mechanical inspection:** Assemble the chassis and check that both wheels rotate freely with power disconnected.
- [ ] **02 — Power inspection:** Verify motor-driver power and logic connections separately.
- [ ] **03 — Continuity inspection:** Check polarity, continuity, and the absence of shorts before connecting the battery.
- [ ] **04 — Emergency-stop test:** Test the emergency-stop circuit without software running.
- [ ] **05 — Controller startup:** Power the STM32 with the motor driver disabled.
- [ ] **06 — Encoder verification:** Verify encoder direction and counts at low wheel speed.
- [ ] **07 — Sensor verification:** Verify current and voltage readings against a multimeter or suitable reference instrument.
- [ ] **08 — Communication test:** Test UART communication with the motors disabled.
- [ ] **09 — Motor test:** Run low-duty-cycle motor tests with the chassis securely supported.
- [ ] **10 — Safety test:** Test command timeout, watchdog behavior, and stop response.
- [ ] **11 — Controlled trial:** Conduct initial moving tests at low speed in a clear, controlled area.

> [!CAUTION]
> Do not use a software watchdog as the only protection against motor-driver faults or a failed embedded controller.


---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=180&color=0:080808,50:450A0A,100:FF3030&text=SOFTWARE%20ARCHITECTURE&fontColor=FFFFFF&fontSize=34&fontAlignY=55&animation=fadeIn" width="100%" alt="RAVEN-X Software Architecture"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PART_III-SOFTWARE_ARCHITECTURE-FF3030?style=for-the-badge&labelColor=080808" alt="Part III"/>
  <img src="https://img.shields.io/badge/ROS_2-DISTRIBUTED_ROBOTICS-FFFFFF?style=for-the-badge&labelColor=181818" alt="ROS 2"/>
  <img src="https://img.shields.io/badge/STM32-EMBEDDED_CONTROL-FF3030?style=for-the-badge&labelColor=080808" alt="STM32"/>
</p>

<p align="center">
  <strong>INTELLIGENCE ABOVE. DETERMINISTIC CONTROL BELOW.</strong>
  <br/>
  <sub>EDGE COMPUTING · EMBEDDED CONTROL · CROSS-LAYER DIAGNOSIS</sub>
</p>

---

## <img src="https://img.shields.io/badge/09-SOFTWARE_STACK-FF3030?style=for-the-badge&labelColor=111111" alt="09 Software Stack"/>

The proposed high-level software consists of:

- **Linux on NVIDIA Jetson** — high-level computation and hardware integration.
- **ROS 2** — distributed robotics software and inter-node communication.
- **C++** — performance-sensitive ROS 2 nodes.
- **Python** — diagnosis, data processing, logging, and experimentation.
- **STM32 firmware** — motor control and local safety supervision.
- **YAML** — configuration and parameter management.
- **CSV or a structured database** — experimental records and telemetry.
- **Git** — version control.
- **Optional containerization** — reproducible software deployment.

### 09.1 — Version compatibility

Version compatibility is a project requirement, not a minor installation detail. The ROS 2 Humble documentation lists Ubuntu 22.04 64-bit ARM among its supported binary targets.

<p align="center">
  <a href="https://docs.ros.org/en/humble/">
    <img src="https://img.shields.io/badge/ROS_2-Humble_Documentation-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS 2 Humble Documentation"/>
  </a>
</p>

Before deployment, freeze a compatible combination of JetPack, Ubuntu, ROS 2, drivers, and software packages. Record the selected versions in the thesis and project configuration.

> [!IMPORTANT]
> Compatibility must be verified for the actual Jetson hardware and software image. Do not assume that every JetPack, Ubuntu, ROS 2, and driver combination is interchangeable.

---

## <img src="https://img.shields.io/badge/10-ROS_2_NODE_ARCHITECTURE-DC2626?style=for-the-badge&labelColor=111111" alt="10 ROS 2 Node Architecture"/>

The ROS 2 architecture separates telemetry acquisition, physical-consistency analysis, fault diagnosis, recovery supervision, and data logging into distinct software components.

### 10.1 — Node architecture matrix

| Node | Responsibility | Example input | Example output |
|:---|:---|:---|:---|
| `serial_bridge` | Communication with STM32 | Serialized telemetry | `/raven/telemetry` |
| `sensor_adapter` | Normalizes sensor messages | IMU, current, and battery data | Standardized telemetry |
| `consistency_node` | Calculates residuals and consistency indicators | Commands and sensor state | `/raven/consistency` |
| `diagnosis_node` | Classifies suspected faults | Residuals and health flags | `/raven/diagnosis` |
| `safety_supervisor` | Applies high-level motion constraints | Requested velocity and system state | Permitted velocity |
| `logger_node` | Records data and diagnostic events | Telemetry and diagnoses | CSV/database records |
| `ml_inference_node` | Optional anomaly inference | Feature vector | Anomaly score |
| `robot_state_publisher` | Publishes robot geometry | Robot description and joint states | TF transforms |
| LiDAR driver | Publishes range scans | Sensor data | `/scan` |
| IMU driver | Publishes inertial measurements | IMU packets | `/imu/data` |
| Navigation stack | Localization and path planning | Map, scans, odometry, and goal | Motion request |

<sub>INTERFACE NOTE: Node names, topic names, and message definitions are proposed conventions. Final interfaces depend on the selected drivers and implementation.</sub>

### 10.2 — End-to-end data flow

```mermaid
flowchart TB
    subgraph INPUT["01 / SENSOR INPUT"]
        S["Wheel Encoders"]
        I["IMU"]
        C["Motor Current"]
        B["Battery Monitor"]
        L["LiDAR / Camera"]
    end

    subgraph MCU["02 / EMBEDDED CONTROL"]
        M["STM32 Firmware"]
        T["Telemetry Acquisition"]
        V["Command Validation"]
        D["Motor Driver"]
        M --> T
        V --> D
    end

    subgraph EDGE["03 / ROS 2 EDGE COMPUTING"]
        SB["serial_bridge"]
        SA["sensor_adapter"]
        PC["Physical Consistency"]
        AN["Anomaly Detection"]
        FD["Fault Diagnosis"]
        RS["Recovery State Machine"]
        LG["Experiment Logger"]

        SB --> SA
        SA --> PC
        PC --> AN
        AN --> FD
        FD --> RS
        PC --> LG
        FD --> LG
    end

    CMD["Permitted Motion Request"]

    S --> M
    I --> M
    C --> M
    B --> M

    T --> SB
    L --> SA

    RS --> CMD
    CMD --> V

    classDef sensor fill:#102A43,stroke:#38BDF8,color:#FFFFFF,stroke-width:2px
    classDef embedded fill:#20202A,stroke:#94A3B8,color:#FFFFFF,stroke-width:2px
    classDef edge fill:#102D28,stroke:#2DD4BF,color:#FFFFFF,stroke-width:2px
    classDef recovery fill:#35151A,stroke:#F87171,color:#FFFFFF,stroke-width:2px

    class S,I,C,B,L sensor
    class M,T,V,D embedded
    class SB,SA,PC,AN,FD,LG edge
    class RS,CMD recovery

    style INPUT fill:#090D14,stroke:#38BDF8,color:#FFFFFF
    style MCU fill:#090D14,stroke:#94A3B8,color:#FFFFFF
    style EDGE fill:#090D14,stroke:#2DD4BF,color:#FFFFFF
```

The Jetson-side safety supervisor provides an additional safeguard, but the final embedded controller must still enforce command limits and communication timeouts.

> [!CAUTION]
> A high-level recovery request is not a substitute for embedded safety enforcement. The STM32 must reject invalid commands and maintain the defined local safe behavior if communication is lost.

---

## <img src="https://img.shields.io/badge/11-COMMUNICATION_PROTOCOL-FF3030?style=for-the-badge&labelColor=111111" alt="11 Communication Protocol"/>

For the first prototype, **USB-UART** is usually simpler to bring up than CAN-FD. CAN can be introduced after the control and telemetry pipeline works reliably.

### 11.1 — Proposed telemetry message

```text
protocol_version
message_type
sequence_number
timestamp
left_encoder_count
right_encoder_count
left_wheel_speed
right_wheel_speed
left_motor_current
right_motor_current
battery_voltage
imu_ax
imu_ay
imu_gz
firmware_state
fault_flags
checksum
```

### 11.2 — Proposed command message

```text
protocol_version
message_type
sequence_number
command_timestamp
left_wheel_target
right_wheel_target
requested_mode
command_validity_period
checksum
```

### 11.3 — Communication requirements

- [ ] Reject messages with invalid length or checksum.
- [ ] Reject invalid numeric values, including non-finite values.
- [ ] Detect duplicate, stale, and out-of-order commands.
- [ ] Track missing sequence numbers.
- [ ] Define explicit units and scaling factors.
- [ ] Include a monotonically increasing sequence number.
- [ ] Apply a timeout if valid commands stop arriving.
- [ ] Record communication failures in the event log.
- [ ] Prevent received commands from overriding embedded speed, acceleration, or hardware safety limits.

### 11.4 — Integrity versus authentication

A checksum detects accidental corruption; it does not authenticate the sender.

If malicious message injection is within the threat model, authenticated communication, key management, replay protection, and access controls must be designed separately.

<p align="center">
  <img src="https://img.shields.io/badge/PROTOCOL_DESIGN-VALIDATE_%7C_MONITOR_%7C_REJECT-FF3030?style=for-the-badge&labelColor=080808" alt="Protocol Design"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=180&color=0:080808,45:450A0A,100:FF2020&text=PHYSICAL%20CONSISTENCY&fontColor=FFFFFF&fontSize=35&fontAlignY=55&animation=fadeIn" width="100%" alt="Physical Consistency Engine"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PART_IV-PHYSICAL_CONSISTENCY_ENGINE-FF3030?style=for-the-badge&labelColor=080808" alt="Part IV"/>
  <img src="https://img.shields.io/badge/CORE-RESIDUAL_ANALYSIS-FFFFFF?style=for-the-badge&labelColor=181818" alt="Residual Analysis"/>
</p>

<p align="center">
  <strong>DETECT THE DEVIATION. EVALUATE THE EVIDENCE.</strong>
  <br/>
  <sub>PHYSICAL MODELS · SENSOR CONSISTENCY · CALIBRATED FAULT REASONING</sub>
</p>

---

## <img src="https://img.shields.io/badge/12-RESEARCH_CONCEPT-DC2626?style=for-the-badge&labelColor=111111" alt="12 Research Concept"/>

The Physical Consistency Engine compares observations that should agree under a specified operating condition.

For example, if the robot is moving on a high-traction floor, wheel-derived forward velocity should broadly agree with an independent body-motion estimate. If wheel speed rises while body motion remains low, the disagreement may indicate wheel slip or a sensor problem.

The system should not simply average every measurement. Measurements have different failure modes, noise characteristics, update rates, and coordinate frames. A diagnosis decision should therefore consider the availability, freshness, uncertainty, and independence of the evidence.

### 12.1 — Physical consistency pipeline

```mermaid
flowchart TD
    A["Timestamped Sensor Measurements"]
    B["Validate Data Availability"]
    C["Check Freshness and Uncertainty"]
    D["Evaluate Operating Conditions"]
    E["Estimate Expected Behavior"]
    F["Calculate Residuals"]
    G["Evaluate Persistence"]
    H["Compare Independent Evidence"]
    Q{"Evidence Sufficient?"}
    J["Maintain Monitoring"]
    K["Generate Fault Hypothesis"]
    R["Pass Evidence to Recovery Policy"]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> Q
    Q -->|No| J
    Q -->|Yes| K
    K --> R

    classDef input fill:#102A43,stroke:#38BDF8,color:#FFFFFF,stroke-width:2px
    classDef analysis fill:#102D28,stroke:#2DD4BF,color:#FFFFFF,stroke-width:2px
    classDef decision fill:#35151A,stroke:#F87171,color:#FFFFFF,stroke-width:2px
    classDef monitor fill:#3A2A10,stroke:#FBBF24,color:#FFFFFF,stroke-width:2px

    class A,B,C input
    class D,E,F,G,H,K analysis
    class Q,R decision
    class J monitor

    style Q fill:#35151A,stroke:#F87171,color:#FFFFFF,stroke-width:2px
```

<sub>CONCEPTUAL DESIGN — the actual algorithms, thresholds, and recovery behavior must be established and validated during implementation.</sub>

---

## <img src="https://img.shields.io/badge/13-RESIDUAL_CALCULATION-FF3030?style=for-the-badge&labelColor=111111" alt="13 Residual Calculation"/>

Let \(x_i\) be a measurement and \(\hat{x}_i\) the corresponding expected value. Define a normalized residual:

\[
r_i = \frac{x_i-\hat{x}_i}{\sigma_i+\epsilon}
\]

**Where:**

- \(x_i\) — measured value.
- \(\hat{x}_i\) — predicted or reference value.
- \(\sigma_i\) — representative uncertainty or noise scale.
- \(\epsilon > 0\) — small constant that prevents division by zero.

A normalized residual measures disagreement relative to the selected noise or uncertainty scale. Its threshold should be estimated from healthy data and validated using fault experiments.

### 13.1 — Example residuals

<details open>
<summary><strong>01 / Wheel-speed residual</strong></summary>

\[
e_{\text{wheel}} =
v_{\text{encoder}}-v_{\text{reference}}
\]

Measures disagreement between encoder-derived velocity and an independent reference estimate.

</details>

<details open>
<summary><strong>02 / Command-tracking residual</strong></summary>

\[
e_{\text{track}} =
v_{\text{command}}-v_{\text{encoder}}
\]

Measures the difference between commanded and encoder-derived velocity. A large residual may be associated with inadequate tracking, increased mechanical load, actuator problems, or encoder faults.

</details>

<details open>
<summary><strong>03 / Yaw-rate residual</strong></summary>

\[
e_{\text{yaw}} =
\omega_{\text{gyro}}-\omega_{\text{odometry}}
\]

Compares gyroscope-derived yaw rate with the estimate derived from wheel odometry. The measurements must use consistent timestamps, coordinate conventions, and filtering assumptions.

</details>

<details open>
<summary><strong>04 / Electrical-power residual</strong></summary>

\[
e_{\text{power}} =
P_{\text{measured}}-P_{\text{expected}}
\]

Measures disagreement between measured electrical power and a reference model.

The power model must account for motor speed, load, driver losses, and measurement placement. A simple fixed current threshold is not sufficient to diagnose every motor fault.

</details>

> [!NOTE]
> Residuals are diagnostic indicators, not unique fault identifiers. Different faults can produce similar residual patterns. Reliable diagnosis requires additional evidence and experimental validation.

---

## <img src="https://img.shields.io/badge/13.2-CONSISTENCY_SCORE-DC2626?style=for-the-badge&labelColor=111111" alt="13.2 Consistency Score"/>

One possible bounded consistency score is:

\[
C =
\exp\left(
-\sum_i w_i
\min\left(
\frac{|e_i|}{s_i+\epsilon},
r_{\max}
\right)
\right)
\]

**Where:**

- \(C\) — consistency score.
- \(e_i\) — residual \(i\).
- \(w_i\) — nonnegative weight assigned to residual \(i\).
- \(s_i\) — normalization scale for residual \(i\).
- \(\epsilon > 0\) — small constant that prevents division by zero.
- \(r_{\max}\) — upper limit applied to the normalized residual contribution.

The score lies between zero and one under the stated nonnegative-weight and positive-denominator assumptions. Higher values indicate lower aggregate disagreement under the selected model.

> [!IMPORTANT]
> This score is an engineering feature, not a probability of robot health. Its meaning depends on the selected residuals, weights, normalization scales, and saturation limit. It must be calibrated and evaluated before any decision threshold is treated as meaningful.

---

## <img src="https://img.shields.io/badge/14-THRESHOLD_CALIBRATION-FF3030?style=for-the-badge&labelColor=111111" alt="14 Threshold Calibration"/>

A threshold is a decision boundary, not a universal physical constant.

For example, a current limit depends on the motor, load, driver, supply voltage, sensor placement, and measurement bandwidth. An IMU residual depends on sensor noise, calibration, filtering, and robot dynamics.

### 14.1 — Calibration workflow

1. **Collect healthy telemetry.** Record representative motor loads, speeds, and operating conditions.
2. **Repeat healthy trials.** Include expected floor surfaces and battery conditions.
3. **Estimate residual distributions.** Characterize variation during normal operation.
4. **Select candidate thresholds.** Use a target false-alarm rate or a justified engineering constraint.
5. **Collect fault data separately.** Record controlled fault-injection trials with appropriate ground-truth labels.
6. **Evaluate detection performance.** Measure false positives and missed detections on held-out runs.
7. **Freeze the thresholds.** Do this before final evaluation to reduce tuning bias.
8. **Record calibration provenance.** Store threshold values, dataset versions, and calibration settings.

For a residual whose healthy distribution is approximately Gaussian, a threshold based on a multiple of its standard deviation may be a useful initial candidate. The Gaussian assumption must be checked rather than assumed.

### 14.2 — Persistence and hysteresis

Use persistence checks and hysteresis to reduce transient alarms.

For example, an advisory anomaly may require repeated out-of-range samples before it is reported as a persistent fault. However, an independent hardware overcurrent protection must act according to its own electrical safety design and must not wait for a software persistence window.

<p align="center">
  <img src="https://img.shields.io/badge/RESEARCH_PRINCIPLE-CALIBRATE_%7C_VALIDATE_%7C_REPRODUCE-FF3030?style=for-the-badge&labelColor=080808" alt="Calibration Principle"/>
</p>

---

<p align="center">
  <sub>RAVEN-X · CROSS-LAYER PHYSICAL CONSISTENCY · FAULT REASONING · BOUNDED RECOVERY</sub>
</p>



