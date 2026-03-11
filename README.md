# mobile-manipulator-planning
Mobile Manipulator Motion Planning Environment (Python)

Includes:

- Nonholonomic mobile base
- 6DOF manipulator
- Random obstacle environment
- Mobile manipulator RRT planner
- Visualization tools
- Optional PyBullet simulation
- Optional ROS2 bridge

---

# System Architecture

Mobile Manipulator State:
[x, y, θ, q1, q2, q3, q4, q5, q6]

RRT in joint + base configuration space

# Installation

```bash
git clone https://github.com/xueboyang/mobile-manipulator-planning.git

cd mobile-manipulator-planning

pip install -r requirements.txt
