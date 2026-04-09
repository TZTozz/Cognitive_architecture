# Cognitive_architecture
Subgroup B2: Advanced Manipulation Strategies

## Assignment B2a: Internal Grasping for Perforated/Hollow Objects

What to do: Develop intelligent internal grasping behaviors for
perforated, hollow, or ring-shaped objects using inverse grasping
strategies with force feedback and sim-to-real validation.
1) Set up UR5e + 2FG7 model in IsaacSim with ROS2 bridge for internal
grasping scenarios
2) Implement inverse grasping strategies for objects with holes or
internal cavities
3) Use force feedback to detect internal contact and regulate expansion
force
4) Create manipulation primitives such as insert, expand, extract, and
internal pull
5) Validate sim-to-real transfer on different rigid perforated objects

Software needed: IsaacSim, MoveIt2, ROS2 Humble, force control
libraries, gripper control interface

Research needed: Internal grasping methods, force-based manipulation,
contact detection, sim-to-real transfer for rigid objects

Deliverables: IsaacSim setup for internal grasping, inverse grasping
strategy library, sim-to-real validation report for perforated objects

## How to run
1. Open Isaac Sim
2. File -> Open -> usd -> robots -> mir250_cabinet_ur5e_2fg7_test.usd
3. Window -> Script Editor
4. Copy and paste the Main.py for the simulation

-> ADD in the modules folder your scripts and into config folder the configurations. 
