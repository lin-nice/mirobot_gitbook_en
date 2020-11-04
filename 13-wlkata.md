# <center>13. Working principle and specification</center>
&ensp;&ensp;&ensp;&ensp;This chapter describes the working space, working principle, size and key technical specifications of WLKATA Mirobot.

##Working space
The workspace of WLKATA Mirobot.

<center><img src="http://lin88zhang.gitee.io/image_en/12/12-1.jpg" width="600"> </center>

##Coordinate system
&ensp;&ensp;&ensp;&ensp;WLKATA Mirbot has a six-joint coordinate system and a Cartesian space coordinate system.

<center><img src="http://lin88zhang.gitee.io/image_en/0/0-2.png" width="350"> </center>

<center>Six-joint coordinate system Of WLKATA Mirobot</center>
<center><img src="http://lin88zhang.gitee.io/image_en/0/0-3.png" width="350"> </center>

<center>Reference frame (Cartesian space coordinate system) of WLKATA Mirobot</center>

1 Joint coordinate system: the coordinate system determined by reference to each moving joint.<br/>
&ensp;&ensp;&ensp;&ensp;•This manipulator has six joints: j1 j2 J3 J4 J5 J6, all of which are rotary joints. The positive rotation direction of each joint follows the right-hand rule and the thumb points to the opposite direction of the output shaft of each shaft motor.<br/>
2 Cartesian coordinate system: The coordinate system is determined by reference to the base of the manipulator.<br/>
&ensp;&ensp;&ensp;&ensp;•The origin of the coordinate system is the center of the base platform.<br/>
&ensp;&ensp;&ensp;&ensp;•The x-axis direction is perpendicular to the fixed base forward.<br/>
&ensp;&ensp;&ensp;&ensp;•The y-axis direction is perpendicular to the fixed base to the left.<br/>

##Sports function
&ensp;&ensp;&ensp;&ensp;The motion modes of Mirobot manipulator include Joint motion mode and Coordinate mode.<br/>
1 Joint motion mode: <br/>
&ensp;&ensp;&ensp;&ensp;the Joint motion mode means that each joint of the manipulator is controlled separately. You can click the joint motion button to move a single joint.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J1 +" and "J1 -" to control the positive and negative rotation of the base motor.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J2 +" and "J2 -" to control the positive and negative rotation of boom motor.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J3 +" and "J3 -" to control the positive and negative movement of jib motor.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J4 +" and "J4 -" to control the positive and negative rotation of the fourth axis at the end.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J5 +" and "J5 -" to control the positive and negative rotation of the fifth axis at the end.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "J6 +" and "J6 -" to control the positive and negative rotation of the sixth axis at the end.<br/>
2 Cartesian motion mode:<br/>
&ensp;&ensp;&ensp;&ensp;The Cartesian motion mode of the manipulator controls the position and attitude of the en-effector. You can click the coordinate and RPY angle motion buttons to change the position and attitude of the end actuator.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "x +" and "X -" to control the manipulator to move along the positive and negative direction of the X-axis.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "Y +" and "Y -" to control the manipulator to move along the positive and negative direction of the Y-axis.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "Z +" and "Z -" to control the manipulator to move along the positive and negative direction of the Z-axis.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "PX +" and "PX -" and the end posture of the manipulator rotates along the X-axis.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "py +" and "py -" to rotate the end posture of the manipulator along the Y-axis.<br/>
&ensp;&ensp;&ensp;&ensp;•Click "PZ +" and "PZ -" and the end posture of the manipulator rotates along the Z-axis.<br/>
&ensp;&ensp;&ensp;&ensp;The Cartesian motion mode supports point-to-point motion mode and linear interpolation motion mode. Please refer to the WLKATA Mirobot communication instructions for specific modes information.<br/>

##Technical specifications
**<center>Parameter specifications</center>**

| name | parameter |
| :------: | :------: |
| Axle number | 6+1 |
| Payload | 150g |
| Repeated positioning accuracy | 0.2mm |
| Communication Interface | USB/WiFi */Bluetooth |
| Power supply voltage | 100V-240V, 50/60 Hz |
| Power input | 12V/5ADC |
| Power | 60W Max |
| Working environment | -10°C~60°C |
**<center>Axis motion parameters</center>**

| Shaft | working range | maximum speed |
| :------: | :------: | :------: |
| Axis 1 | -100° to +100° | 31°/s |
| Axis 2 | -60° to +90° | 65°/s |
| Axis 3 | -180° to +50° | 28°/s |
| Axis 4 | -180° to +180° | 110°/s |
| Axis 5 | -180° to +40° | 33°/s |
| Axis 6 | -180° to +180° | 66°/s |
**<center>Physical characteristics</center>**

| name | parameter |
| :------: | :------: |
| Net weight (manipulator and controller) | 1.5kg |
| Round base size | ＜diameter160mm |
| Material of manipulator | Aluminum alloy, ABS engineering plastics |
| Controller | Arduino2560 |
| Robot installation | Desktop |
| Package specification (L×w×h) | 220mm×160mm×270mm |
| The dimension of standard outer box (L × w × h) | 300mmx200mmx400mm |

##Technical parameters
&ensp;&ensp;&ensp;&ensp;The size parameters of WLKATA Mirobot are shown in Figure below.
<center><img src="http://lin88zhang.gitee.io/image_en/12/12-3.png" width="400"  > </center>
&ensp;&ensp;&ensp;&ensp;The installation hole size of its end flange is shown in Figure below.
<center><img src="http://lin88zhang.gitee.io/image_en/12/12-4.png" width="350"  > </center>


