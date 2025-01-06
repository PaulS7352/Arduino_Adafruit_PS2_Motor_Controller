# Arduino_Adafruit_PS2_Motor_Controller
Code for Arduino that allows you to control motors using the Adafruit motor shield and cytron PS2 Controller Shield

#Wired Code (Helicopter setup)
I set variables for controlling a set of 3 motors that plug into the arduino directly. These will be subject to change based on your configuration. Motors need to be in analog pins for variable control (PWM).
The helicopter set up refers to one joystick being used for elevation (Vertical Movement) and the other used to control 2 other motors for horizantal movement.


*Note*
In all of the code I have the horizontal motors set up in zones for directional control and in some code for reduced power. These directions and power settings are dictated by the x and y coordinated reported by the joysticks.
