# 🤖 Mobility Management

Our robot uses a rear-wheel drive system optimized for speed and stability on flat surfaces.

## 🔧 Hardware Setup

- Drive Motors:  
  - 1 × Medium Motor powering both rear wheels
- Steering Mechanism:
  - 1 × Servo Motor mounted at the front
  - Connected to the front wheels via gears
- Chassis Connection:
  - Components are secured using bolts, screws, and Velcro patches**

![Mobility Diagram](../images/mobility-diagram.png) <!-- optional image -->

## ⚙️ Design Philosophy

Since the competition environment involves a **flat surface with no object-pushing requirement**, we focused on:
- **Speed over Torque** to ensure quick and efficient task completion
- **Simplicity in Movement Control** through a minimal motor setup

## 🧠 Coding Simplicity

By using only:
- **1 Medium Motor** for driving both rear wheels
- **1 Servo Motor** for steering

...we simplified the logic required for movement and turning, making the robot more reliable during autonomous runs.

---

📌 _Note: Motor and servo configurations can be adjusted via the main movement script located in `/code/movement-control.py`._
