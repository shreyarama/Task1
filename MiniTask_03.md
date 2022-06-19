# Debugging

For both the projects, before proceeding with part by part debugging, first check to see if all the modules (Bluetooth, Arduino, Motor Driver) light up. If you find that any particular module does not light up, then that module has been shorted and needs to be replaced.

Also, if you find an unusually hot IC/module, that usually means that component has been burnt out and needs to be replaced.

After checking for these two, proceed with the below debugging tutorials.

## IOT Based Smart Security Surveillance Robot debugging tutorial

#### Step 1: First, always check for hardware issues. Check the wiring and make sure all the pins are connected correctly and that there is no loose contact.

#### Step 2: Check to see if the servos are damaged. Typically, a broken servo will have unmeshed gears and will rotate without any resistance. Overheating is also a sign of damage and the servo will have to be replaced.

#### Step 3: Check to see if the wheel motors have been damaged. If the motors rotate properly, then the problem is probably with the motor driver.

#### Step 4: Check the Bluetooth module using the procedure given in https://github.com/aswinkumar1999/Elec_iBot_Session#testing-bluetooth.

#### Step 5: Use diode testing mode on the multimeter to check if LEDs are damaged. Replace if damaged.

#### Step 6: If the Bluetooth and Motor Driver modules all light up but the code is not getting uploaded to the Arduino and if it is hot, then the Arduino is probably burnt.However, shorting an Arduino is pretty hard to do, so make sure that all other possible problems have been eliminated before concluding that the Arduino has been shorted.

#### Step 7: If all hardware is working properly, then move onto the software debugging and check the code for bugs.


## Gesture Controlled Robot

#### Step 1: Once again, always check for hardware issues first. Check the wiring and connections. Make sure there are no loose contacts.

#### Step 2: Check the HC12 Bluetooth module using the procedure given in https://github.com/aswinkumar1999/Elec_iBot_Session#testing-bluetooth.

#### Step 3: Check to see if the wheel motors have been damaged. If the motors rotate properly, then the problem is probably with the motor driver.

#### Step 4: As mentioned earlier, if all other modules work properly yet the problem still persists, then the Arduino has probably been shorted. However, make sure you have exhausted all other possible malfunctions before drawing this conclusion. 

#### Step 5: If all hardware is working properly, then move onto the software debugging and check the code for bugs.
