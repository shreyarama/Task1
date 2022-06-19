# Documentation of chosen projects

### Project 1: IOT Based Smart Security Surveillance Robot

In this project, we aim to build a smart surveillance robot which transmits live video feed and can be remotely controlled by us using a connected local device. The robot will also have IR sensors for obstacle detection. We will also be implementing user authentication system so as to enable multiple users functionality.

![](https://github.com/shreyarama/Task1/blob/main/ezgif.com-gif-maker.gif)

#### Personal Notes:
We could add in an alarm module which could be triggered by the user from the remote device. This would help alert the people around in case of an emergency. 

We could use custom PCBs to make this robot as compact as possible. Then, we could build a compact version of this surveillance robot which could help us get video footage from hard to reach places like under the bed / between the wall and cupboard, etc. 


### Project 2: SmartSlippers - Movement recognition for old people

In this project, we build a non-invasive wearable device that straps onto slippers and sends notifications to an Android app if a fall is detected. The device also displays the time since last detected activity and the total active time. Additionally, this device also has pedometer functionality.

#### Personal Notes: 

In order to give this device wider usage other than just fall detection, we will need to use a more diverse dataset with our ML model, to enable the device to recognise more subtle movements. It would also make our device become more accurate.

This device is also currently powered by a power bank, so we need to add a small battery to power the device.

In the future, we could also look at integrating this device inside a waterproof slipper framework, instead of the current design where it is just taped to the top of a slipper. For this we would have to make the circuit more compact, for which we would have to design a custom PCB instead of using Arduino.

### Project 3: Autonomous Rubik's Cube Solving Robot

In this project, we aim to build an autonomous Rubik's Cube solving robot. We use Fusion 360 for 3D modelling the framework for the robot and 3D print it. This project also uses PiCamera and Raspberry Pi Zero 2 for the computer vision part. We also use the Kociemba solver to calculate the most efficient algorithm for solving the cube.

#### Personal Notes:

This project could be expanded to solve any cube by installing sensors in the "arm" parts of the robot. The arm will then sense the size of the cube and adjust itself to grip the cube. The PiCamera could be used to detect the size of the cube, and choose the correct solving algorithm accordingly.


### Project 4: Gesture Controlled Robot

In this project, we build a gesture controlled robot using Arduino. We use the HC12 wireless module to transmit data from the sensor to the robot. We also use a PAJ7620 sensor to implement the gesture recognition functionality.

This project has two parts: the Transmitter and the Receiver.

The Transmitter consists of the PAJ7620 sensor to sense gestures, an Arduino to process the signal and a HC12 wireless module to transmit the signal to the Receiver.

The Receiver consists of a HC12 wireless module that receives the signal sent out by the Transmitter and an Arduino to process the signal.

#### Personal Notes:

We could extend this project to a plant-watering robot by adding in water dispenser functionality to the robot. Gesture control would make watering the plants very easy. 

We could also program in additional gestures to stand for particular functions; for example, a snap of the finger could stand for turning off the water supply (in the case of the irrigation robot exmaple), etc other than the usual forward, backward, rotate gestures. This would give our robot wider application.


### Project 5: DIY Home Automation System

In this project, we use NodeMCU to build a home automation system for turning on and off the  lights. We use the Blynk app control the lights.

#### Personal Notes:

Since NodeMCU has very wide functionality in IOT, we could extend our home automation system to also control other appliances like fans. It can also be used for room temperature and humidity control.

We can also use NodeMCU as a security system, to notify us if there is a break-in. It could also give us live video feed from our home. 

Thus, we can extend this project to create the perfect home automation system for our home, thanks to the customisability of NodeMCU.

