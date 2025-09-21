# Simulation-Based Design and Analysis of a Vent Cleaning Robot

**Research Project | Department of Electrical Engineering, University of Moratuwa, Sri Lanka**  

---

## Project Overview

Air ducts in HVAC systems require regular cleaning to maintain airflow, energy efficiency, and healthy indoor air quality. Accumulated dust, debris, and clogs reduce efficiency and pose health risks such as allergies and respiratory problems.  

This project presents a **vent cleaning robot** designed to navigate ducts, break dust clumps, and assist vacuum cleaning. The robot combines lightweight aluminum alloy construction, a wheel-track locomotion system, rotating brushes, and a sensor module for autonomous navigation and cleaning.  

A **3D model** was built in SolidWorks, and **Simulink simulations** validated the operational dynamics of the robot and sensor modules.  

---

## Key Features

- **Autonomous Cleaning:** Robot can identify clogs and dust clusters in air ducts and clean them efficiently.  
- **Mobility:** Wheel-track system made of polyurethane for stable movement on dusty or slippery surfaces, including vertical ducts.  
- **Rotary Brush:** Effectively scrubs duct surfaces to dislodge accumulated dust.  
- **Sensor Module:** Includes ultrasonic sensors and camera modules to detect obstacles, clogs, and monitor cleaning progress.  
- **Control System:** Provides precise navigation, brush actuation, and integration with simulation models for testing and validation.  

---

## System Components

### Mechanical Design
- **Body:** Lightweight aluminum alloy for durability and easy maneuverability.  
- **Wheels & Tracks:** Polyurethane tracks for stability and adhesion inside ducts.  
- **Rotary Brush:** Plastic bristles for effective dust removal.  

### Sensors & Navigation
- **Ultrasonic Sensors:** Detect obstacles and dust clumps up to 1 meter.  
- **Infrared Camera Module:** Confirms obstacles and triggers brush operation.  
- **Control System:** Ensures precise movement and brush actuation.  

### Power & Actuation
- **Battery System:** High-performance Li-ion batteries with BMS for stable, long-duration operation.  
- **Motors:** DC motors drive both wheels/tracks and the rotating brush.  

---

## Software Components

- **SolidWorks:** Used for detailed 3D modeling of the robot, including body, wheels, brush, and sensors.  
- **MATLAB Simulink:** Simulates the robot’s control system, sensor readings, and actuator responses.  
- **Simscape Integration:** Imports SolidWorks model to Simulink for dynamic simulation of sensors and motors.  

---

## Workflow

1. Robot moves through air ducts using its wheel-track locomotion.  
2. Ultrasonic sensors detect obstacles or dust clusters.  
3. Camera and sensor module confirms dust clumps.  
4. Rotating brush is activated to dislodge debris.  
5. Cleaning cycle continues until the duct is clear.  
6. Data from sensors can be analyzed through Simulink simulations to validate performance.  

---
## Benefits

- Reduces manual labor in duct cleaning.  
- Improves HVAC system efficiency and energy consumption.  
- Promotes healthier indoor air quality.  
- Supports autonomous operation in hard-to-reach areas.  

---

## Future Work

- Integrate autonomous vacuum system within the robot.  
- Monitor air quality inside ducts during operation.  
- Improve battery capacity for longer operational periods.  
- Develop fully autonomous navigation using AI-based path planning.  

---

## License

This project is shared for educational and research purposes. Please contact the authors for reuse or collaboration.
