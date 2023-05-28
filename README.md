![GitHub all releases](https://img.shields.io/github/downloads/Aftershock3995/ArduinoCodeSystem/total?color=%23ff0000&logo=GitHub) ![GitHub commit activity](https://img.shields.io/github/commit-activity/w/Aftershock3995/ArduinoCodeSystem?color=%23ff0000&logo=GitHub) 
# ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) `Pedal Controller Alpha Code`


This code is in early alpha; the app code has not been published, as well as the pedal code has not been updated to work with the app.

### ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) `Installation`
Download and install the Arduino IDE.
Connect the Arduino board to your computer.
Open the .ino file in the Arduino IDE.
Compile and upload the code to the board.
Connect the stepper motors, encoders, limit switches, and load cells to the appropriate pins on the board.

### ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) `Usage`
Power on the board.
Press the pedal to move it forward.
Release the pedal to stop it.
The load cell value for each pedal is displayed in the serial monitor.
To home the pedals, run the homePedals() function (currently N/D).
Adjust the pedal settings in the code if necessary.

### ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) `App early alpha`

<img src="https://cdn.discordapp.com/attachments/868329637602816081/1112417905699725422/image.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

### ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) `Credits`
This code was created by Aftershock.
The code uses the following libraries:

[AccelStepper](https://www.airspayce.com/mikem/arduino/AccelStepper/)

[Encoder](https://www.pjrc.com/teensy/td_libs_Encoder.html)
