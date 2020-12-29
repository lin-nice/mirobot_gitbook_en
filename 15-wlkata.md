# <center>Appendix I</center>
##WLKATA Mirobot Calibration Operation
**Calibration Operation Procedure:**<br/>
&ensp;&ensp;&ensp;&ensp;The Mirobot is calibrated before leaving the factory. In each time the manipulator finishes the HOMING action, the joint 1, joint 2, joint 3, joint 4 and joint 5 should be homed to the pre-designed homing position.<br/>
&ensp;&ensp;&ensp;&ensp;After the HOMING action, if one or more of the joints is/are not in the pre-designed homing position, one need to re-calibrate the manipulator. The Calibration procedure is explained as below:<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/14/14-1.png" width="600"  > </center>
&ensp;&ensp;&ensp;&ensp;Step 1: Turn on the power of the robotic arm. Open the "COMMAND" interface of Mirobot Studio software, enter "M50" and click "Send" to unlock each axis.
<center><img src="http://lin88zhang.gitee.io/image_en/14/14-2.png" width="600"  > </center>
&ensp;&ensp;&ensp;&ensp;Step 2: Enter the "SETTING" interface, click "Calibration-Start". 
<center><img src="http://lin88zhang.gitee.io/image_en/14/14-3.png" width="600"  > </center>
&ensp;&ensp;&ensp;&ensp;Step 3: In JOINT MODE, control each axis to the corresponding position by adjusting the "J1~J6" on the right side of the interface.<br/>
<font color="red">Note: The 4th axis must be adjusted through negative steps (J4-). There has No special requirements for other axes. The 6th axis does not need Calibration.</font>
<div align="center">
<img src="http://lin88zhang.gitee.io/image_en/14/14-4.png" width="250"><img src="http://lin88zhang.gitee.io/image_en/14/14-5.png" width="250"><img src="http://lin88zhang.gitee.io/image_en/14/14-6.png" width="250">
</div>
<div align="center">
Joint 1 homing position reference&ensp;&ensp;&ensp;&ensp;Joint 2 homing position reference&ensp;&ensp;&ensp;&ensp;Joint 3 homing position reference
</div>

<div align="center">
<img src="http://lin88zhang.gitee.io/image_en/14/14-7.png" width="250"><img src="http://lin88zhang.gitee.io/image_en/14/14-8.png" width="250">
</div>
<div align="center">
Joint 4 homing position reference&ensp;&ensp;&ensp;&ensp;Joint 5 homing position reference
</div>
<center>Pre-designed homing position of the Joint 1 to Joint 5</center>

&ensp;&ensp;&ensp;&ensp;Step 4: After each axis rotates to the corresponding position, enter the "STTING" interface again and click "Finish".
<center><img src="http://lin88zhang.gitee.io/image_en/14/14-9.png" width="600"  > </center>
&ensp;&ensp;&ensp;&ensp;Step 5: After completing the calibration, click HOMING. The posture of the robot arm after homing is shown in the figure below.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-22.png" width="400"  > </center>
<center>The correct manipulator position after a successful HOMING action</center>