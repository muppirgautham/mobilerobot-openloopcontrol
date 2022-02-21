# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure

Step1:
Initiate the MobileRobot

<br/>

Step2:
Connect your PC with the MobileRobot.

<br/>

Step3:
Open Python program.



<br/>

Step4:
Program the movements of the robot using python code.
<br/>


Step5:
Execute the python program.
<br/>

## Program:
```
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis

    ## Write your code here
    from robomaster import robot
import time

if name == 'main':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis

   
    x = x-axis movement distance,( meters) [-5,5]
    y = y-axis movement distance,( meters) [-5,5]
    z = rotation about z axis ( degree)[-180,180]
    xy_speed = xy axis movement speed,( unit meter/second) [0.5,2]
   
    ep_chassis.move(x=2.6, y=0, z=0, xy_speed=1).wait_for_completed()
    ep_chassis.move(x=0, y=0, z=45, xy_speed=1).wait_for_completed()
    ep_chassis.move(x=3.5, y=0, z=0, xy_speed=.75).wait_for_completed()
    ep_chassis.move(x=0, y=-0.3, z=0, xy_speed=.75).wait_for_completed()
    ep_chassis.move(x=0, y=0, z=50, xy_speed=.75).wait_for_completed()
    ep_chassis.move(x=.2, y=0, z=0, xy_speed=.75).wait_for_completed()
    ep_robot.close()



    
    ep_robot.close()
   ```
## MobileRobot Movement Image:

![robo](./img/robomaster.png)

Insert image here:
![WhatsApp Image 2022-02-21 at 08 58 17](https://user-images.githubusercontent.com/94810884/154876770-c258ceb5-73e3-4ddd-aa31-f837c4f45ca2.jpeg)
![WhatsApp Image 2022-02-21 at 08 58 17 (1)](https://user-images.githubusercontent.com/94810884/154876843-7371bbd3-8db1-4fb1-ad61-f2d0e13e4ead.jpeg)




<br/>
<br/>
<br/>
<br/>

## MobileRobot Movement Video:

Upload your video in Youtube and paste your video-id here: https://youtu.be/Fj4BgwQbgCg

<br/>
<br/>
<br/>
<br/>

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College


