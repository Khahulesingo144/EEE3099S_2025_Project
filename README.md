
# Micromouse Project 2025

Welcome to the **Micromouse Project 2025** repository! This project is part of the EEE3097S, EEE3098S, and EEE3099S courses at the University of Cape Town. It focuses on the procedural and system-level design of an autonomous micro-mouse capable of navigating a maze using a combination of MATLAB, Simulink, and Stateflow tools.

## 🎯 Objectives

This project aims to:

- Build on prior design experience (from EEE3088F).
- Use formal design methods to develop a system-level solution.
- Simulate, implement, and test control strategies for autonomous maze navigation.
- Design robust software models that can be deployed to physical hardware via embedded code generation.

By the end of this project, the micro-mouse should autonomously:
- Explore and map a maze.
- Determine an optimal path.
- Navigate from a start point to a target as efficiently as possible.

---

## 🛠️ Tools and Technologies

- **MATLAB**
- **Simulink**
- **Stateflow**
- **Embedded Coder** (for code generation)
- **Hardware platform**: Custom micro-mouse with differential drive

---

## 📁 Project Structure
### Milestone 1

- **M1 sim: The mouse moves in a straight line for 2m and stops. Encoders are used to ensure the mouse moves straight and for distance measurement using 8 ticks per revolution**
- **M1 practical: The mouse moves in a straight line for 1.5m and stops. The built-in gyro angle is connected to a PID controller to ensure minimal heading error and provide straight-line motion, while encoders      measure distance at 8 ticks per revolution. The performance varied due to different lighting conditions.**

- **M2 sim: The mouse explores a maze in simulation. A mixture of gyro angle and TOF sensor reading is used to ensure the mouse can effectively explore and map a maze in simulation. Some functionalty is also         added to remove any noise from the gyro and TOF sensors.**
- **M2 practical: The mouse explores a physical 6*4 maze. TOF sensors are used to ensure the mouse is able to move in a straight line, turns are time-based as encoder ticks, and the gyro proved inconsistent.**

---

## 🚀 Milestones

### ✅ Milestone 1: Straight Line Movement
- **Goal**: Move a fixed distance (e.g., 2m) using closed-loop control.
- **Assessment**: Simulated and physical run, plus a report.

### 🔄 Milestone 2: Maze Mapping (Simulation)
- **Goal**: Fully explore a simulated maze.
- **Assessment**: Simulink simulation and documentation.

### 🎉 Final Demo: Physical Maze Navigation
- **Goal**: Real-world maze traversal and optimal path execution.
- **Assessment**: Live demonstration, Stateflow model, sensor logs, and video.

---

## 📦 Submissions

Each milestone includes:
- `.slx` control model
- Sensor logs and video (where applicable)
- Report documenting the design and process flow

---

## 📚 Learning Resources

- MATLAB Onramp, Simulink Onramp, and Stateflow Onramp
- [Student Mobile Robotics Training](https://www.mathworks.com/academia/student-competitions/robotics.html)
- [Engineering Educator Academy YouTube: Robotics Playlist](https://www.youtube.com/playlist?list=PLn8PRpmsu08pzi6EMiYnRbsN9FW-wfTqb)
- Gavin Nielson’s YouTube Playlist on Simscape modeling
- [Gazebo Simulator](http://gazebosim.org/)

---

## 🔗 Related Repository

👉 [UCT Micromouse GitHub Repository](https://github.com/EEEUCT/Micromouse)

---

## 📌 Notes

This is a living project and may be updated throughout the course. Documentation and files will evolve as each milestone is reached and refined.

---

## 👥 Contributors

Tlangelani Tembe - TMBTLA001
Khahule Singo - SNGKHA008

---

## 📃 License

This project is for educational use and follows the UCT EEE department's academic policies.

