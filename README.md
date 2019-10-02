# Paper Puppets

*A lab report by Sandra Ebirim.*

## In this Report

To submit your lab, clone [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab4). You'll need to describe your design, include a video of your paper display in operation, and upload any code you wrote to make it move.

## Part A. Actuating DC motors

**Link to a video of your virbation motor**

[Vibration Motor](https://www.youtube.com/watch?v=jXh6Pbm6ISY&feature=youtu.be)



## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**

The red wire goes to power, the orange wire goes to signal, and the brown wire goes to ground. 

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

The signal should be attached to pin 9 or 10 because it requires a PWM pin. According to the code, pin number 9 should be used in this particular instance. 

**b. What aspects of the Servo code control angle or speed?**

To control the angle, the value that is used as limits for the variable pos need to be altered. For example, to change the angle from 180 degrees to 270 degrees, the code must be changed from: 

![before](https://github.com/sandraebirim/IDD-Fa19-Lab4/blob/master/before.png)

to

![after](https://github.com/sandraebirim/IDD-Fa19-Lab4/blob/master/after.png).

To change the speed of the servo motor, the delay in the loop() function must be altered. Decreasing the delay from 15 to 5 has the following result: 

[Faster Servo](https://www.youtube.com/watch?v=d9DlvF41WF8&feature=youtu.be)


## Part C. Integrating input and output

**Include a photo/movie of your raw circuit in action.**

I altered the code so that the speed of the servo motor is based on the output of the pentotiometer.

[Video](https://www.youtube.com/watch?v=2rkcp7yW368&feature=youtu.be)

[Circuit Code](https://github.com/sandraebirim/IDD-Fa19-Lab4/blob/master/PentServo.ino)


## Part D. Paper puppet

**a. Make a video of your proto puppet.**

[Video](https://www.youtube.com/watch?v=CTDGOM_rDu0&feature=youtu.be)

## Part E. Make it your own

**a. Make a video of your final design.**

Ghost moves more in the dark than in the light. 

[Ghost Final Design](https://www.youtube.com/watch?v=b5Ck_G1WbTU&feature=youtu.be)

[Ghost Code](https://github.com/sandraebirim/IDD-Fa19-Lab4/blob/master/GhostCode.ino)
