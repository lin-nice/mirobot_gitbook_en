# <center>7. Using the Python programming</center>
&ensp;&ensp;&ensp;&ensp;Please be aware that WLKATA Studio supports Python 3.8 and below.
##Step 1.Preparation
&ensp;&ensp;&ensp;&ensp;(1) Switch to Python function in the WLKATA Studio by click the PYTHON tab in the software interface.<br/>
&ensp;&ensp;&ensp;&ensp;(2) Please DO NOT change the first 8 lines of code in the python window.  <br/>

***
<span class="left"><img src="http://lin88zhang.gitee.io/image_en/0/0-19.png" width="60" ></span>**Please <font color="red">DO NOT change or delete the first 8 lines </font>of code in the python window, or the manipulator may run discordant and cause illegal motions.**<br/>
***
<center><img src="http://lin88zhang.gitee.io/image_en/7/7-1.png" width="600"> </center>
<center>DO NOT change or delete the first 8 lines of code in the python window</center>

##Step 2. Quick command library in the Python programming
&ensp;&ensp;&ensp;&ensp;There are three groups of Quick commands in the library, the Action options, Angle control options and Coordinate control options. Double click the Quick command and the code will be inserted into the command line.<br/>
The list of Quick command and description is as below:

| Quick commands group | Quick command | Description |
| :------: | :------: | :------:|
| **Action options** |  |  |
| Homing | api.home_simultaneous() | Perform the homing routine on all axis at the same time. |
| Unlock | api.unlock_shaft() | Unlock the shaft enabling movement.|
| Go to zero | api.go_to_zero() | Send each axis to its 0 position. |
| Suction cup on | api.suction_cup_on() | Switch on the suction cup. |
| Suction cup off | api.suction_cup_off() | Switch off the suction cup. |
| Slider move to | api.slider_move_to(x, speed) | Move the slide rail to the specified position. |
| Conveyor Move to | api.conveyor_move_to(ConveyorMode.relative, 0, 1500) | Move the slide rail to the specified position |
| Set Delay Time | api.set_delay_time(1) | Delay the next action after the specified time |
| **Angle control options** |  |  |
| Go to axis | api.go_to_axis(0,0,0,0,0,0,1500) | Mirobot moves from the current position to the specified position in the angle mode. |
| Increment of each axis | api.increment_axis(0,0,0,0,0,0,1500) | Mirobot moves from the current position to the specified position |
| Move axis | api.move_to_axis(MirobotJoint.Joint1, RevolveDirection.cw, 0, 1500) | Rotate specify axis the specified value in the specified direction |
| **Coordinate control options** |  |  |
| Go to Cartesian position | api.go_to_cartesian_lin(202,0,181,0,0,0,1500) | Mirobot moves from the current position to the specified position in the coordinate mode. |
| The increment in Cartesian space | api.increment_cartesian_lin(0,0,0,0,0,0,1500) | Mirobot moves specified number of coordinates in specified direction. |
| Directional movement | api.direction_mobility(MoveDirection.forward, 0, 1500) | Mirobot moves specified coordinates independently from the current position in the specified direction |
| Jump move | api.jump_move(ConveyorMode.relative, 0, 0, 0, 1500) | Jump move to the specified position. |
| Arc move | api.set_arc_move(MoveMode.relative, RevolveDirection.cw, 0, 0, 0, 60, 1500) | move in an arc path |

##Step 3. An example of Python programming
```
#version python 3.8
#coding=utf-8
from mirobot import *
from time import sleep
api=Mirobot()
#Please do not delete the above code
api.home_simultaneous()          #Home Mirobot
sleep(15)                       #Delay 15s
for i in range(10):                #Repeat the following actions 10 times
api.go_to_axis(30,0,0,0,0,0,1500)   #The first axis rotates from the zero position to  
the absolute position + 30 at 1500°/min
api.go_to_axis(-30,0,0,0,0,0,1500)   #The first axis rotates from the zero position to  
the absolute position -30 at 1500°/min
api.go_to_zero()                  #Back to zero
```

