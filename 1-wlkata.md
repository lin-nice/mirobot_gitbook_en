# <center>1. Quick start guide of Mirobot</center>
&ensp;&ensp;&ensp;&ensp;This chapter briefly introduces how to control the manipulator by using WLKATA Studio, so that users can quickly understand and use the manipulator. The overall process of operation is shown in Figure below.<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-0.PNG" width="400" > </center>
<center>The quick start flow chart of using WLKATA Mirobot manipulator</center>

##Step 1. Power adapter and USB cable connection 
(1) Use the supplied USB data cable to connect the WLKATA Mirobot and your computer. 
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-1.png" width="300" > </center>
<center>Connecting the manipulator to the computer</center>
(2) Connect the supplied power adapter to the manipulator.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-2.png" width="300" ></center>
<center>Connecting the manipulator to the power adapter</center>

##Step 2. Powering on and off WLKATA Mirobot

***
<span class="left"><img src="http://lin88zhang.gitee.io/image_en/0/0-19.png" width="60" ></span>**DO NOT Twisting the Joint 1 or Joint 3 by Hand No Matter the Manipulator Is Powered On or Off!**<br/>
Since this would lead to a fetal damage to the gears of these joints. (See the 2.2 Precautions in this manual)<br/>
***
Power on:<br/>
&ensp;&ensp;&ensp;&ensp;Ensure to connect the manipulator with supplied power adapter. Press the ON/OFF power button on the top of the 
manipulator base to power on the device. The green power indicator on the ON/OFF button will light up.

<div align="center"><img src="http://lin88zhang.gitee.io/image_en/1/1-3.png" width="300"><img src="http://lin88zhang.gitee.io/image_en/1/1-4.png" width="300"></div>
<center>Switching on the manipulator</center>

Power off:<br/>
&ensp;&ensp;&ensp;&ensp;Press the power button on the top of the base of the manipulator again to switch off the power. The power indicator light on the button will turned off.<br/>

##Step 3. Installing the driver and WLKATA Studio
Studio Studio The users can control the Mirobot by using WLKATA Studio software to realize functions such as Joint Mode control, Coordinate Mode control, Teaching & Play, Blockly control and Drawing, etc.<br/>

###3.1 System environment requirements
WLKATA Studio control software supports the following operating systems:<br/>
&ensp;&ensp;&ensp;&ensp;•Windows 7 (64 bit)，Windows 8 (64 bit)，Windows 10 (64 bit)<br/>

###3.2 Downloading WLKATA Studio and the driver packages
Download WLKATA Studio software package and the CH340 driver package from <http://www.wlkata.com/site/download.html>.

###3.3 Installing and verification the driver
1.Installing driver<br/>
&ensp;&ensp;&ensp;&ensp;Decompress the driver package, and click SETUP.exe in the directory to install the CH340 driver. In the pop-up window, click INSTALL and the interface will pop up after successful installation. Click OK.<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-5.png" width="300" ></center>
<center>CH340 driver installation wizard interface</center>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-6.png" width="300" ></center>
<center>Driver installed successfully</center>
2.Verifying the driver<br/>
&ensp;&ensp;&ensp;&ensp;(1) Ensure to connect the manipulator to the computer by using the supplied USB data cable.<br/>
&ensp;&ensp;&ensp;&ensp;(2) Open the Device Manager in your PC windows system. Ensure to tick the Show hidden devices option in the View menu. If the "USB-serial ch340 (COM4)" can be found in the port (COM and LPT), it means the driver is installed successfully. The port number following the COM may be different depends on the default driver installation of your system. 
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-7.png" width="600" ></center>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-8.png" width="600" ></center>
<center>Serial port drive information of the WLKATA Mirobot manipulator</center>

##Step 4. Installing and verification of WLKATA Studio
1.Installing WLKATA Studio<br/>
&ensp;&ensp;&ensp;&ensp;Log in to the official website: www.wlkata.com. Click "Support-Download Center". Choose "Wlkata Studio-Win-v1.015.zip (Alpha version)" to download.<br/>
&ensp;&ensp;&ensp;&ensp;WLKATA Studio software package can be directly decompressed and used. <br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-9.png" width="600" ></center>
&ensp;&ensp;&ensp;&ensp;Decompress the WLKATA Studio software package to a local root directory such as D:\ or E:\ to avoid potential foreign language character disturb. Double-click Wlkata Studio.exe in the directory to open the software user interface. <br/>
<font color="red">Note: The parent directory file of the software can only be English name.</font><br/>


<center><img src="http://lin88zhang.gitee.io/image_en/1/1-10.png" width="600" ></center>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-11.png" width="600" ></center>
<center>WLKATA Studio interface</center>
2.Verifying WLKATA Studio Software<br/>
&ensp;&ensp;&ensp;&ensp;In the decompressed package, double-click to open the Wlkata studio.exe. If the Wlkata Studio software can be opened correctly, it means that the WLKATA Studio software is running successfully.<br/>
3.Verifying the device connection<br/>
&ensp;&ensp;&ensp;&ensp;(1) Open the Wlkata Studio.exe. The software should automatically search and connect to the manipulator after a few seconds. When successfully connects to the manipulator, the upper left corner of the WLKATA Studio interface should display the CONNECTED blue icon.<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-12.png" width="600" ></center>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-13.png" width="600" ></center>
<center>WLKATA Studio can search and connect to the manipulator automatically</center>
&ensp;&ensp;&ensp;&ensp;(2) If the software did not connect to the manipulator automatically, please manually connect the manipulator by click SETTING to set "Port" and "Baud Rate". Enter the correct serial port COM_ number ( as found in the step (2) in the content of 2.Verifying the driver ). After clicking "OK", there will be "Connected" displayed in the upper left corner.<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-14.png" width="400" ></center>
<center>Manually setting a serial port number in the Setting if the manipulator is not connected automatically</center>

##Step 5. Brief Introduction of WLKATA Studio Control Software
&ensp;&ensp;&ensp;&ensp;WLKATA Studio is a control software for Mirobot. It includes command control, joint/coord control, teaching, graphical programming, python programming, writing and drawing, firmware upgrade and other functions.<br/>

###5.1 Chinese and English switch:
&ensp;&ensp;&ensp;&ensp;After opening the software, click SETTING to set the language, select English or Chinese, confirm and restart. (It can also be set by clicking "EN" in the upper right corner of the interface).
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-15.png" width="600" ></center>

###5.2 Joint/Coord Mode switch
&ensp;&ensp;&ensp;&ensp;In the Commond mode, select "JOINT MODE" or “COORD MODE” at the top of the user interface, and the selected mode will be displayed as a white background status.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-16.png" width="600" ></center>

###5.3 Introduction to SETTING interface
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-17.png" width="600" ></center>
&ensp;&ensp;&ensp;&ensp;（1）Serial port settings: set the serial port and baud rate (115200) of the robotic arm which connected to Mirobot Studio. <br/>
&ensp;&ensp;&ensp;&ensp;（2）Drawing settings: set drawing speed (recommending the default value)<br/>
&ensp;&ensp;&ensp;&ensp;（3）Calibration: used to calibrate the robotic arm.<br/>
&ensp;&ensp;&ensp;&ensp;（4）Reset: reset all data of the robotic arm (recalibration is required after reset)<br/>
&ensp;&ensp;&ensp;&ensp;（5）Language: Set language and font (After language setting, click OK to automatically restart the software to take effect. After font setting, click OK to manually restart the software to take effect) Or click the "EN" button in the upper right corner of the interface to switch between Chinese and English.<br/>

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-18.png" width="600" ></center>

&ensp;&ensp;&ensp;&ensp;（6）End Effector: select the end tool and rail/belt mode used by the robotic arm. <br/>

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-19.png" width="600" ></center>

&ensp;&ensp;&ensp;&ensp;（7）Firmware: update the firmware, refer to "Mirobot Firmware Upgrade Tutorial" for detailed operation. <br/>

##Step 6. Start using the manipulator
&ensp;&ensp;&ensp;&ensp;This chapter describes the essential control operation of this manipulator by using the WLKATA Studio software.

###6.1 Prerequisite
&ensp;&ensp;&ensp;&ensp;•The driver and WLKATA Studio software have been installed successfully. For details, please refer to the 3.2 Installing the driver and WLKATA Studio software.<br/>
&ensp;&ensp;&ensp;&ensp;•The manipulator has been correctly connected to the computer, and the power supply of the manipulator has been turned on. Please refer to 3.3 Powering on and off WLKATA Mirobot for detailed operation.<br/>

###6.2 Preparing operation steps
1.Connecting WLKATA studio with the manipulator <br/>
&ensp;&ensp;&ensp;&ensp;Double click the Wlkata Studio.exe in the directory, and the Mirobot Studio interface should pop up. Then please follow the steps of 3.3.4 to verify the driver and connection. When the connection is succeeded, the CONNECTED blue icon should be displayed in the upper left corner of the WLKATA Studio interface.<br/>
2.HOMING the manipulator before any operation<br/>
&ensp;&ensp;&ensp;&ensp;Before any operation, the manipulator must be homed to the pre-designed homing position. Click the HOMING button in the WLKATA Studio. Wait for the manipulator to be homed. Figures in below shows the manipulator during the homing process, and the correct position of the manipulator after a successful HOMING action.<br/>
<font color="red">Note: If the HOMING action is failed or interrupted, please reapply the power of manipulator and repeat the HOMING action again.</font><br/>

***
<span class="left"><img src="http://lin88zhang.gitee.io/image_en/0/0-19.png" width="60" ></span>**The manipulator must be HOMING again on each time reapplying power from a power failure or an emergency stop, or re-opened the WLKATA Studio. One should wait for the HOMING action to be fully completed before any further operation.**<br/>
***

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-20.png" width="600" ></center>

<center>Doing the HOMING action each time powering on the manipulator</center>

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-21.png" width="500" ></center>

<center>In the progress of HOMING the manipulator</center>

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-22.png" width="300" ></center>

<center>The correct manipulator position after a successful HOMING action</center>

3.Software emergency stop and reset<br/>
&ensp;&ensp;&ensp;&ensp;In case of any illegal operation of the manipulator, click the STOP button immediately in the Mirobot Studio to trigger a software emergency **stop** operation.<br/>
&ensp;&ensp;&ensp;&ensp;After the emergency stop operation, press the **RESET** button on the top of the manipulator base to recover the device from the emergency status. <br/>
&ensp;&ensp;&ensp;&ensp;After press the RESET button, please **HOMING** the manipulator in the software again before continuing using the manipulator.<br/>

***
<span class="left"><img src="http://lin88zhang.gitee.io/image_en/1/1-23.png" width="60" ></span>**After a software emergency stop, press RESET on top of the base, and do the HOMING again before continuing using the manipulator.**<br/>
***

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-24.png" width="600" ></center>

<center>Emergency stop button in the WLKATA Studio</center>

<center><img src="http://lin88zhang.gitee.io/image_en/1/1-25.png" width="300" ></center>

<center>Pressing RESET button on the base of the manipulator after a software emergency stop</center>

###6.3 Using the ROBOT JOINT MODE control function
&ensp;&ensp;&ensp;&ensp;STEP(1) Click the COMMAND tab in the software interface.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-26.png" width="600" ></center>
&ensp;&ensp;&ensp;&ensp;STEP(2) Switch to the ROBOT JOINT MODE in the upper control modes selection panel.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-27.png" width="600" ></center>
<center>Selecting the ROBOT JOINT MODE</center>
&ensp;&ensp;&ensp;&ensp;STEP (3) Click each of the J+ J- control buttons on the right panel to control the motion of each of the six joints of the manipulator separately. The speed can be adjusted by input Speed value, and the step can be adjusted by input Step value.
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-28.png" width="600" ></center>
<center>Selecting the ROBOT JOINT MODE</center>

###6.4 Using the COORDINATE MODE control function 
&ensp;&ensp;&ensp;&ensp;STEP(1) Click the COMMAND tab.<br/>
&ensp;&ensp;&ensp;&ensp;STEP(2) Switch to COORDINATE MODE in the control modes selection panel.<br/>
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-29.png" width="600" ></center>
<center>Selecting the COORDINATE MODE</center>
&ensp;&ensp;&ensp;&ensp;STEP (3) Click each of the control button on the right panel of the WLKATA Studio to control the spatial position and attitude (XYZ coordinate and RX RY RZ angle) of the End-effector of the manipulator. The speed can be adjusted by input Speed value, and the step can be adjusted by input Step value. 
<center><img src="http://lin88zhang.gitee.io/image_en/1/1-30.png" width="600" ></center>
<center>The COORDINATE MODE control panel</center>
