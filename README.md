# Genetic-Algorithm-for-Epuck-robot
This project makes use of Genetic algorithm to help a an epuck robot navigate about a maze using [Webot](https://cyberbotics.com/)

### Video Demo 
[![Genetic Algorithm](https://img.youtube.com/vi/cfNjr1UXDn8.jpg)](https://www.youtube.com/watch?v=cfNjr1UXDn8)

## Guide
```
To launch the world:
1.goto worlds/e-puck_Robotics_TMaze.wbt
2.Run Simulation and press 'R' to demo the best result.
3.Press 'S' to start GA training
```
Four python codes are used to run this simulation.
Listed as follows
```
1.epuck_python - CW.py    -  Robot controller
Located in controllers\epuck_python - CW

2.supervisorGA - CW.py    -  Supervisor
Located in controllers\supervisorGA - CW

3.ga.py   -    functions used by the supervisor
Located in controllers\supervisorGA - CW

4.mlp.py  -    functions used by the robot controller
Located in controllers\epuck_python - CW
```
