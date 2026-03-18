# Astrum-Domini
Astrum Domini is an Action RPG that blends high-speed space combat with tactical squad leadership. 
Set in the year 2225, players navigate a solar system at war, balancing fleet-scale strategy with intense dogfighting.

**Status:** <code style="color : green">In Development</code>

*This repository serves as a technical portfolio. The source code is maintained in a private repository to protect project IP.*




### Fleet AI & Traffic Control System
To manage thousands of active fighters over high-density areas like Earth, I developed a **Hierarchical Squad Command System**
Fighters follow dynamic vector targets provided by the leader, drastically reducing pathfinding overhead for massive fleet battles

https://github.com/user-attachments/assets/ab065ef2-f6a4-44cc-b5ae-8221fbbbbd67

### Extensive object pooling optimiazations
To manage the very high projectile and effects in a scene I developed a burst pooling system that works even with a world origin shift to continue working in various physics conditions across a to scale solar system.

https://github.com/user-attachments/assets/0ff8055f-5a73-47d3-893c-3c3d87ad8117


### Procedural Physics & Kinematics
Implemented a procedural generation system for destructible 3D debris.
Asteroids utilize efficient kinematic rotations and collisions, allowing for high volumes of objects on screen without performance dips.

### Real-Time Solar System AIS
Developed a persistent, 2D-inspired **Automated Identification System (AIS)** for space traffic in 3D
