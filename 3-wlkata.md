# <center>3. Using the BLOCKLY function</center>
&ensp;&ensp;&ensp;&ensp;Blockly is an open-source graphical programming platform created by Google, which is easily to be learnt and applied by starters.

##Step 1. Introduction of Blockly panel
&ensp;&ensp;&ensp;&ensp;Click the BLOCKLY tab in the software interface to switch to Blockly panel.<br/>
&ensp;&ensp;&ensp;&ensp;Drag and drop the Blockly module from the Selection Panel 1 to the Programming Panel 2 to program. The Code Panel 3 would show the python codes of the Blockly module on the Programming Panel. Drag the dividing axis to adjust the size of the work area or hide the code area.<br/>
<center><img src="http://lin88zhang.gitee.io/image/3/3-1.png" width="350"> </center>
<center>The Blockly graphic programming funtion</center>

##Step 2. Basic functions 
&ensp;&ensp;&ensp;&ensp;New: create new folder<br/>
&ensp;&ensp;&ensp;&ensp;Open: open a local file<br/>
&ensp;&ensp;&ensp;&ensp;Save: save the file, which is saved to the “data” directory by default<br/>
&ensp;&ensp;&ensp;&ensp;Save As: save the modified file<br/>
&ensp;&ensp;&ensp;&ensp;Export: export Gcode to a local folder<br/>
&ensp;&ensp;&ensp;&ensp;Download: download Gcode to the robotic arm sub control board<br/>
&ensp;&ensp;&ensp;&ensp;Run: run the code in the work area<br/>
&ensp;&ensp;&ensp;&ensp;Step: choose a code block in the work area, and run the code in separate steps<br/>

##Step 3. Blockly programming module
&ensp;&ensp;&ensp;&ensp;There are 14 commonly used programming code blocks in the action options:
<center><img src="http://lin88zhang.gitee.io/image/3/3-2.png" width="350"> </center>
&ensp;&ensp;&ensp;&ensp;Reset：homing the Mirobot<br/>
&ensp;&ensp;&ensp;&ensp;Zero position: the Mirobot moves from the current position to the full zero position under the angle mode. <br/>
&ensp;&ensp;&ensp;&ensp;Pause send() seconds: the next instruction is issued after the program delays the specified time.<br/>
&ensp;&ensp;&ensp;&ensp;Delay time () seconds: execute the next instruction after the specified time.<br/>
&ensp;&ensp;&ensp;&ensp;Position move(): Mirobot moves from the current position to the specified position in the coordinate mode.<br/>
&ensp;&ensp;&ensp;&ensp;Move (forward/backward/up/down) number () speed (): move the specified coordinate number from the current position in the specified direction.<br/>
&ensp;&ensp;&ensp;&ensp;Suction cup (on / off): control the opening or closing of suction cup.<br/>
&ensp;&ensp;&ensp;&ensp;Gripper (open/close): control the opening or closing of the end tools.<br/>
&ensp;&ensp;&ensp;&ensp;Slider move to () speed (): control the slide rail to move to the specified position.<br/>
&ensp;&ensp;&ensp;&ensp;Conveyor move (relative position/absolute position) speed (): control the conveyor belt to move to the specified position.<br/>
&ensp;&ensp;&ensp;&ensp;Rotation Angle: the Mirobot robot arm moves from the current position to the specified position in the angle mode. <br/>
&ensp;&ensp;&ensp;&ensp;Turn (joint X) (counter/clockwise) : let the Mirobot Specify joint move clockwise or counterclockwise to the designated coordinates.<br/>
&ensp;&ensp;&ensp;&ensp;Door track movement: move to the specified relative or absolute position with the gate trajectory.<br/>
&ensp;&ensp;&ensp;&ensp;Arc trajectory movement: draw the arc according to the requirements of arc trajectory movement.<br/>

##Step 4. A sample of Blocly programming: making the robotic arm move
<center><img src="http://lin88zhang.gitee.io/image/3/3-3.png" width="350"> </center>
Action explanation：<br/>
&ensp;&ensp;&ensp;&ensp;Homing the robotic arm<br/>
&ensp;&ensp;&ensp;&ensp;The following actions cycle 10 times<br/>
&ensp;&ensp;&ensp;&ensp;The robotic arm move from the "zero position" to point A at a speed of 1500mm/min. The coordinate is "X202Y0Z20", and the end posture remains unchanged. <br/>
&ensp;&ensp;&ensp;&ensp;The robotic arm moves from point A to point B at a speed of 1500mm/min. The coordinate is "X202Y0Z200", and the end posture remains unchanged. <br/>
&ensp;&ensp;&ensp;&ensp;The robotic arm returns to the zero position from point B at a speed of 1500mm/min. <br/>
&ensp;&ensp;&ensp;&ensp;The first axis rotates to the absolute position + 20°at a speed of 1500°/ min. <br/>
&ensp;&ensp;&ensp;&ensp;The first axis rotates to the absolute position - 20°at a speed of 1500°/ min. <br/>
&ensp;&ensp;&ensp;&ensp;The robotic arm returns to zero position.<br/>


