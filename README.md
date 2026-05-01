# ⚡10kW-EV-motorcycle-design
This repository shows an early EV motorcycle design project where I explored electric powertrain integration and mechanical design.  Although this project was done earlier in my learning, it shows how I approach basics like Electronic component sizing &amp; selection, MATLAB simulation and CAD design. 

## 🚀 Key Specifications

* Motor: 10 kW BLDC 
* Battery: 48V NMC Pack (3.7V, 120Ah pack)
* Drive System: Chain Drive (16T / 42T, 96 Link)
* Target Application: Urban + Highway Use
* Wheelbase: 1350 mm
* Ground Clearance: 180 mm
* Seat Height: 800 mm


## 🎯 Project Approach

### 1. Benchmarking & Analytical Modelling

The design process began with competitor analysis of existing motorcycles to establish baseline parameters.

These benchmarks were used to define:

* Vehicle dimensions
* Ergonomics (rider posture range)
* Performance targets


### 2. Powertrain Sizing

Powertrain components were selected based on performance requirements and simulation-driven validation.

* 10 kW BLDC motor selected for target speed and torque
* Chain drive ratio optimized (16T driver / 42T driven)
* Battery configuration derived using real-world driving cycles (MIDC, WMTC)

Simulation was performed using:

* MIDC (Modified Indian Driving Cycle)
* WMTC (Worldwide Motorcycle Test Cycle)

This enabled realistic estimation of:

* Energy consumption
* Range potential
* System efficiency


### 3. Vehicle Dynamics & Layout

Key vehicle parameters were defined to ensure stability and ride quality:

* Rake Angle: 23°
* Trail: 125 mm
* Anti-Squat: ~86%
* Wheel effective diameter: 575 mm

Braking system:

* Front Disc: 320 mm
* Rear Disc: 220 mm


### 4. CAD & Mechanical Design

The motorcycle was developed using a mix of custom-designed and reference-based components.

* ~60% components designed from scratch
* Remaining components sourced from OEM references (e.g., wheels, lights)

### Design Focus:

* Structural packaging
* Ergonomics (95th percentile rider)
* Component accessibility
* Manufacturability


## 💰 Bill of Materials (BOM)

* Total Component Cost: ₹2,38,400
* Estimated Production Cost: ~₹1,97,200

### Insights:

* High initial cost due to off-the-shelf components
* Potential cost reduction up to ~50% at scale
* Additional manufacturing costs (labor, logistics) may increase total cost by ~30%


## 🧠 Key Learnings

* Importance of benchmarking in early-stage design
* Trade-offs between performance, cost, and manufacturability
* Real-world validation using driving cycles (MIDC & WMTC)
* System-level thinking across mechanical and electrical domains


## 🔮 Future Improvements

* Thermal management for battery and motor
* Advanced BMS integration
* Lightweight frame optimization
* Detailed simulation (FEA, durability analysis)


## 🤖 Relevance to Robotics & Automation

This project demonstrates core engineering skills transferable to robotics:

* Motor selection and system sizing
* Mechanical-electrical integration
* CAD-driven design workflows
* Simulation-based decision making


## 👨‍💻 Author

Siddhesh Adavade
Mechanical Design Engineer focused on EV systems, robotics, and spm design.


## ⭐ Notes

This project represents an early-stage system design exercise, showcasing a structured approach to developing an electric vehicle platform from basic principles.
