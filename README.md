# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure
Step1: Initiate the MobileRobot.


Step2: Connect your PC with the MobileRobot through Wi-Fi.


Step3: Open batter_level.py file and check the battery.


Step4: Open the other Python files and Program the movements of the robot using python.


Step5: Execute the python program and record the movements.

## Program
```python
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis

    ## Write your code here



    
    ep_robot.close()
```

## MobileRobot Movement Image:

![robo](./img/robomaster.png)

Insert image here


<img width="1049" height="593" alt="Screenshot 2025-11-04 212841" src="https://github.com/user-attachments/assets/dc949a82-db58-4c29-8ab7-aa02a5ffd104" />


## MobileRobot Movement Video:
https://youtu.be/gUFecqGmTk0?si=x3OpB1ZobyqNzjta

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

```
Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
