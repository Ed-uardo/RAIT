# Indiana Drones – SLAM + Motion Planning (Georgia Tech CS7638)

This project implements a full robotics pipeline combining SLAM (Simultaneous Localization and Mapping) and motion planning for a simulated drone tasked with finding and navigating to a treasure in a forested environment. Developed as part of the Georgia Tech course **CS7638: Artificial Intelligence for Robotics**.

## Project Overview

The assignment was split into two parts:
- **Part A**: Used GraphSLAM to estimate the drone’s position and landmark locations using noisy control inputs and range measurements.
- **Part B**: Designed a motion planner with steering and distance clipping, obstacle detection, and recovery behaviors to guide the drone safely to the treasure.

## Key Features

- GraphSLAM with pose and landmark graph updates
- Handling of action noise and sensor uncertainty
- Greedy planner with steering angle constraints and collision detection
- Obstacle avoidance and alternative path recovery strategies

## Lessons Learned

- How to integrate localization and planning under uncertainty
- The tradeoffs between precision and computational simplicity
- How to implement recovery logic in constrained planners

## Academic Context

This project was completed for academic credit and adheres to Georgia Tech’s honor code. Source code is **not publicly shared** to comply with course policy.

## Demo Part A 

https://github.com/user-attachments/assets/94c5b3ff-22ca-47a0-b280-b6592743cedf

## Demo Part B 

![treasure hunt demo](example.gif)
