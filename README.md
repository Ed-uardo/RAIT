# PID Drone Control – Georgia Tech CS7638

This project implements a PID control system for a simulated dual-rotor drone in a 2D environment. It was completed as part of the Georgia Tech course **CS7638: Artificial Intelligence for Robotics**.

## Project Overview

The goal was to stabilize the drone’s vertical (thrust) and horizontal (roll) motion using PID controllers. The final implementation met performance targets for hover accuracy, response time, and minimal oscillation.

## Key Features

- PID controller implementation for thrust and roll
- Parameter tuning via Twiddle (coordinate descent)
- Handling of integral windup and thrust saturation
- Evaluation across multiple simulation test cases

## Performance Goals

- Reach target altitude within 1.5 seconds
- Minimize overshoot and steady-state error
- Maintain stable hover with minimal oscillation

## Academic Context

This project was completed for academic credit and adheres to Georgia Tech’s honor code. Source code and simulator files are **not publicly shared** to comply with course policies.

## Lessons Learned

- How to tune a PID controller using feedback-based optimization
- The tradeoffs between fast convergence and control stability
- How control theory applies in real-world robotics

## (Optional) Demo GIF or Screenshot

![drone hover demo](example.gif)
