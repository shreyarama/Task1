
# Alternative Approaches / Improvements

## IOT based Smart Security Surveillance Robot

### Problem Statement: "Build a smart surveillance robot which transmits live video feed and can be remotely controlled by us using a connected local device. Also, implement user authentications system to enable multiple users functionality."

* One area where we could improve this design is by designing a custom PCB for the robot, since that would help make our design more compact. A compact robot can be applied to more versatile tasks like giving video feed from hard to reach places.
* Another improvement we could potentially make would be to use mecanum or omni wheels instead of the conventional wheels that they have used, since that would make controlling our robot much easier, thanks to the omni directional movement capability of these wheels.
* Designing the chassis as an octagon with four mecanum/omni wheels at alternate edges would be a better design choice according to me, because that way we could freely rotate the chassis 360 degrees on the spot. This way, we get better movement capabilities and we also do not need a rotating camera stand that way, since the chassis provides the on-the-spot pivoting motion required.

## Gesture Controlled Robot

### Problem Statement: "Build a robot whose movements can be controlled by gestures from the user"

* One improvement we could make is to add in additional gestures, instead of the conventional left, right, front, back gestures. We could add in gestures to stand for specific motions. This would make our robot suited for more varied applications.
* Here, they have chosen HC12 as the Bluetooth transceiver, which is perfect because of its low power consumption, wide range and compact design. However, for cost effectiveness, we could also replace the HC12 with the much cheaper RF module for Arduino, which provides somewhat inferior range (200-300m), but should be more than sufficient for our project.
* We could also mount the transmitter onto a glove, which would make our project much more portable. I also saw a very cool project which was gesture controlled wheelchair for the disabled (https://create.arduino.cc/projecthub/afsh_ad/hand-gesture-control-wheelchair-for-disabled-people-30cf25?ref=tag&ref_id=gesture&offset=5) , for which this transmitter glove would be perfect.
* Arduino is a low voltage microcontroller. So, to control motors through Arduino, we would need to interface them with a motor driver to enable them to get the required high voltage motors need to run. L293D and L298N are both perfect for this job. L293D is the cheaper option.
