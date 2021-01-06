# <center>Multifunctional Extension Module User Manual</center>
##1.Function Introduction
&emsp;&emsp;The multifunctional expansion module is mainly used to expand the external interface of the mechanical arm. Its main functions are:<br/>
&emsp;&emsp;&rArr;Running pneumatic module, gripper, slide rail, conveyor belt and other external equipment<br/>
&emsp;&emsp;&rArr;Running off-line manipulator’s actions<br/>
&emsp;&emsp;&rArr;Extend communication interface, supporting WIFI, BT Bluetooth, RS485 communication protocols<br/>
&emsp;&emsp;&rArr;Displaying manipulator status<br/>

##2.Interface and Appearance

<center><img src="http://lin88zhang.gitee.io/image_en/19/1.jpg" width="600"  > </center>

**Communication Interface:**<br/>
&emsp;&emsp;An IDC cable needs to be connected between the multifunctional expansion module and the manipulator to enable the communication.<br/>
**PWM Port:**<br/>
&emsp;&emsp;The PWM signal output interface is controlled by the robot arm and it outputs PWM signal. It is used for connecting the pneumatic module and the gripper. Its interface voltage is 5V, and the maximum output is 2A.<br/>
**Step Motor Port:**<br/>
&emsp;&emsp;This is the seventh axis stepping motor control port, which is used for connecting sliding rail or conveyor belt.<br/>
**Limit Switch Port:**<br/>
&emsp;&emsp;This is the seventh axis reset switch port, which is used for resetting the seventh axis and the six axes of the robot arm together.<br/>
**Power Output:**<br/>
&emsp;&emsp;The power output interface is used for supplying power to the external equipment. The output voltage is 12V and the maximum current is 1A.<br/>
**RS485 Port:**<br/>
&emsp;&emsp;This is the RS485 communication interface for controlling multiple robot arm manipulators.<br/>
**OLED Screen:**<br/>
&emsp;&emsp;The 1.3-inch OLED screen can display the status information of manipulator.<br/>
**State of the LED Light:**<br/>
&emsp;&emsp;The LED light indicates manipulator’s status:<br/>
&emsp;&emsp;The red light flashes: Offline, the robot arm is initializing.<br/>
&emsp;&emsp;The red light remains on: Alarm, the robot arm is locked.<br/>
&emsp;&emsp;The green light remains on: Idle, the robot arm is standing by.<br/>
&emsp;&emsp;The blue light remains on: Run, the robot arm is during a motion.<br/>
**Navigation Keyboard:**<br/>
&emsp;&emsp;Long pressing the middle OK key for 2 seconds, the robot arm will execute the Homing action.<br/>

##3.Quick Start
###1.Cable Connection

<center><img src="http://lin88zhang.gitee.io/image_en/19/2.jpg" width="400"  > </center>

&emsp;&emsp;Connects the robot arm and the multifunctional expansion module with the IDC cable, as shown in the figure. Then turns on the power supply of the robot arm.

###2.Using the end-effector tools
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the Pneumatic Set/Using the gripper module"
=======
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the gripper module/Using the Pneumatic Set"
=======
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the gripper module/Using the Pneumatic Set"
=======
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the gripper module/Using the Pneumatic Set"
=======
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the gripper module/Using the Pneumatic Set"
=======
<<<<<<< HEAD
&emsp;&emsp;For details, please refer to "Using the gripper module/Using the Pneumatic Set"
=======
&emsp;&emsp;For details, please refer to "Using the Pneumatic Set"
>>>>>>> 6550c3e6f879b88ad7b8f317a718173e1cd1ab48
>>>>>>> a9a641b74c2e1f0f9ffe215d1b4fc56f57ccfafb
>>>>>>> a5b25b6899f06c37c73cf2cfe67a0966c84e4973
>>>>>>> 4bf30be580c9fcbf4e5db2bd397de78c70fe7fb0
>>>>>>> 33568094e86ae0f242955ef1d28674f24ec50fc2
>>>>>>> 38d6acccb088c525eec521ae68069ee9fd972544
###3.Using the mobile phone APP (Only supporting Android system)
&emsp;&emsp;Step 1: Download and install the APP.<br/>
&emsp;&emsp;&emsp;&emsp;Download Address: https://www.wlkata.com/support/download-center

<center><img src="http://lin88zhang.gitee.io/image_en/19/3.jpg" width="600"  > </center>

&emsp;&emsp;Step 2: Turn on the Bluetooth of the mobile phone, and pair the Bluetooth with "Mirobot" ; the password is "7676".<br/>
&emsp;&emsp;Step 3: Open the APP and click Scan. Then click Select Device, and then select and click the following item:

<center><img src="http://lin88zhang.gitee.io/image_en/19/5.jpg" width="300"  > </center>

&emsp;&emsp;Click Connect. If the following status is displayed, the connection is successful.

<center><img src="http://lin88zhang.gitee.io/image_en/19/6.jpg" width="400"  > </center>

&emsp;&emsp;Step 4: Before starting any operation, remember to home the robot arm by either pressing the Homing button on the software, or pressing the middle navigation key on the multifunctional extension module for two seconds. <br/>
&emsp;&emsp;After a successful homing, you can now start an operation.<br/>
###4.Using the teach pendant
&emsp;&emsp;Step 1: Switch on the power of the teach pendant and wait until a blue Bluetooth flag appear on the upper right corner of the screen, which indicates that the Bluetooth connection is successful.<br/>
&emsp;&emsp;Step 2: Before starting any operation through the teach pendant, homing the robot arm by either long pressing the Stop button on the pendant, or long pressing the middle navigation key on the multifunctional extension module for two seconds. <br/>
&emsp;&emsp;After a successful homing, you can now start an operation.<br/>
###5.Offline operation 
&emsp;&emsp;The robot arm can run the pre-downloaded Blockly code in the multifunctional expansion module. To achieve this off-line operation, one needs to download the Blockly code from PC to the multifunctional expansion module.<br/>
&emsp;&emsp;**Part I: Downloading the File (only supporting Blockly at the moment)**<br/>
&emsp;&emsp;Step 1: After editing the Blockly codes in WLKATA Studio, click the "Download" button.<br/>

<center><img src="http://lin88zhang.gitee.io/image_en/19/7.jpg" width="600"  > </center>

&emsp;&emsp;Step 2: Select a location to save the file and input a file name (note: the file name only support English symbols), such as "test". Click OK, and the file should start downloading. If a "GCode Save Completed!" is shown, it indicates the download is successful.<br/>
&emsp;&emsp;**Part II: Running the File in WLKATA Studio**<br/>
&emsp;&emsp;Step 1: To query the list of downloaded files, switch to the Command panel on WLKATA studio, and send an instruction "o110".<br/>

<center><img src="http://lin88zhang.gitee.io/image_en/19/8.jpg" width="600"  > </center>

&emsp;&emsp;Step 2: To run the offline file in the WLKATA Studio,  send a command "o111" + file name, such as:  o111test.<br/>
&emsp;&emsp;If the manipulator returns noIdle, it means that the robot arm is locked. One needs to <font color="red">Homing</font> the robot arm first, and then send the command again.<br/>
&emsp;&emsp;If the manipulator returns OK, the file shall be run successfully.<br/>

<center><img src="http://lin88zhang.gitee.io/image_en/19/9.jpg" width="600"  > </center>

&emsp;&emsp;**Part Ⅲ: Running the File Offline**<br/>
&emsp;&emsp;Step 1: Connect the robot arm and multifunction control module with the IDC cable. If using an end-effector, connect the end-effector cable with the multifunction control module, too.<br/>
&emsp;&emsp;Step 2: Power on the robot arm.<br/>
&emsp;&emsp;Step 3: On the multifunction control module, the red-light start flashing: means the robot arm is **Offline**, please wait till the red-light remaining on. <br/>
&emsp;&emsp;When the red light remains on, it means the the robot arm is locked (Alarm status), now please long press the middle navigation key for 2 seconds, so that the robot arm will homing. After the homing is completed, the manipulator will automatically run the Offline file.
