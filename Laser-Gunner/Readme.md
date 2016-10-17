#Laser Gunner
######A game based on the old arcade game Tail Gunner. Shoot enemy cubes before they attack you. Shoot the enemy in the middle of the screen to start.



![Lasergunner homescreen](http://i.imgur.com/uvOUS4f.jpg)

##Game Settings
Game Settings can be configured in the bottom center of the screen. Lives determines how many lives you start with at the beginning of the game, XY Velocity is the initial x and y velocity of the enemies in the first wave, +XY is the difficulty (i.e. how much the x and y velocity increases after every wave). Likewise, Z Velocity is the initial z velocity of the enemies in the first wave, +Z is the difficulty (i.e. how much the z velocity increases after every wave). 

##Controls
Game controller options are either Joystick (usb gamepad), mouse+keyboard, or the [Android Sensor UDP App.](https://play.google.com/store/apps/details?id=com.ubccapstone.sensorUDP). 

######Mouse and Keyboard
When using Mouse and Keyboard, x range and y range sliders are for x and y calibration respectively. Press 'F' key to fire.

######Joystick
Joystick input uses the D-PAD on a generic USB game controller and any button to fire. The speed slider is to adjust the sensitivity of the crosshair movements.

######[Android Sensor](https://play.google.com/store/apps/details?id=com.ubccapstone.sensorUDP).
In the Android Sensor App- enable gravity sensors, input the ip address and port number shown in the GUI, and hit the "SEND DATA" button. In the sensor app, toggle keyboard by navigating the top right corner menu. This will display a set of buttons on the phone. All buttons are set to fire. The y position of the cursor is mapped to the vertical tilt of the phone (Grav Y). The x position of the cursor is mapped to the twist of the wrist (Grav Z). Use x range and y range sliders to calibrate tilt.

##About Android Sensor UDP
Sensor UDP allows the user to send sensor data wirelessly via UDP on their Android device. Users can use this sensor data for a wide variety of motion tracking applications, or simply read-out the sensor data from their phone.
• Includes support for Linear Acceleration, Gravity, Rotation, Orientation, Ambient Light and Proximity sensors
• Displays sensor values on screen during wireless transmission
• Checks device for sensor availability. It is important to note that not all devices support all sensors.
• Includes a keyboard to 'create notes' for performance

##Laser Controls
Color picker selects laser output color and brightness. IP should match the etherdream IP shown in [sitter](http://ether-dream.com/downloads.html). Blanking set to 4 and a scan rate of about 6,000 yeilds good results. xy scale, offset and keystone controls the laser output geometry. Note: enabling the "Show Border" button on the bottom center of the screen is helpful when calibrating laser output.