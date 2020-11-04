# <center>Appendix III</center>
##Trouble shooting list of WLKATA Studio and Mirobot
&ensp;&ensp;&ensp;&ensp;**1.Upgrading to a newer version WLKATA Studio**<br/>
&ensp;&ensp;&ensp;&ensp;You could find and download the newest version of WLKATA Studio on www.wlkata.com.<br/>
&ensp;&ensp;&ensp;&ensp;Before installing a new version of WLKATA Studio, remember to clear the local record of Wlkata Studio in the AppData directory:<br/>
&ensp;&ensp;&ensp;&ensp;(1)	Go to the directory of C:\User\(User Name)\AppData\Local\ , delete the whole folder of Wlkata Studio in this file path.<br/>
&ensp;&ensp;&ensp;&ensp;(2)	Find the old version of Wlkata Studio.exe directory, and delete the whole folder.<br/>
&ensp;&ensp;&ensp;&ensp;(3)	Decompress the new version of WLKATA Studio software package to a local root directory such as D:\ or E:\ to avoid potential foreign language character disturb. <br/>
&ensp;&ensp;&ensp;&ensp;(4)	Double-click Wlkata Studio.exe in the directory and start to use the WLKATA Mirobot.<br/>
&ensp;&ensp;&ensp;&ensp;**2.If you want to put the Mirobot back into the box, please adjust the Mirobot to the position shown below.**

<center><img src="http://lin88zhang.gitee.io/image_en/16/16-1.png" width="600"  > </center>

&ensp;&ensp;&ensp;&ensp;**3.The first axis sensor failure problem**<br/>
&ensp;&ensp;&ensp;&ensp;(we will resolve this hardware issue in the next version of WLKATA Mirobot)<br/>
&ensp;&ensp;&ensp;&ensp;Cause: The sensor plug is loose or the one-axis screw is loose, resulting in the sensor not detecting the magnet. Follow the steps in below to solve this problem:<br/>
&ensp;&ensp;&ensp;&ensp;Firstly, tighten this screw a little bit:<br/>

<center><img src="http://lin88zhang.gitee.io/image_en/16/16-2.png" width="350"  > </center>

&ensp;&ensp;&ensp;&ensp;Secondly, in the WLKATA studio, do the next 8 steps:

| step | item |
| :------: | :------: |
| 1 | Enter $ 20 = 0 and $ 21 = 0 (Remove software limit) |
| 2 | Enter M50 to unlock the motor |
| 3 | Click J1 to turn the first axis to the position of the scale line to align |
| 4 | Click Homing to see if the reset is successful |
| 5 | Stop immediately if the magnet position is exceeded |
| 6 | If you still have any questions, please contact customer service |
| 7 | If successful, please enter $ 20 = 1 and $ 21 = 1 |
| 8 | Then you should be able to use it normally |
<center><img src="http://lin88zhang.gitee.io/image_en/16/16-3.png" width="600"  > </center>
<center><img src="http://lin88zhang.gitee.io/image_en/16/16-4.png" width="600"  > </center>
<center><img src="http://lin88zhang.gitee.io/image_en/16/16-5.png" width="600"  > </center>