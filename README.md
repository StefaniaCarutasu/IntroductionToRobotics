# IntroductionToRobotics
 Introduction to Robotics laboratory homeworks, taken in the 3rd year at the Faculty of Mathematics and Computer Science, University of Bucharest. Each homework includes requirements, implementation details, code and image files.
 
 # Homework 1 - RGB LED
 
## Requirements

Control a RGB led by using separate potentiometers in controlling each of the colors of the led (Red, Green, Blue). The control must be done with digital electronics.

## Implementation details

Since the values read from each potentiometer are in the interval [0..1023], they need to be mapped to the accepted values by each led which are in the interval [0..255].

## Picture of setup
![](https://github.com/StefaniaCarutasu/IntroductionToRobotics/blob/main/Homework%201/SetupPicture.jpeg)

## Video of setup
[https://youtu.be/_b5cnWRgmag](https://youtu.be/_b5cnWRgmag)


 # Homework 2 - CROSSWALK
 
## Requirements

Implement a crosswalk for both cars and pedestrians controlled by the press of a button. 

## Implementation details

The press of the button launches the sequence: after 10 seconds the light turns yellow for cars. After 3 more seconds, there is red for cars and green for pedestrians with a beeping sound. After another 3 seconds the green led for pedestrians starts blinking and the sound is intermitent. After the sequence is over, it is back to green for cars and red for pedestrians until the button is pressed again. 

## Picture of setup
![](https://github.com/StefaniaCarutasu/IntroductionToRobotics/blob/main/Homework%202/setup_picture.jpeg)

## Video of setup
[https://youtu.be/_b5cnWRgmag](https://youtu.be/YrKpjJNMoQ4)


# Homework 3 - EMF Detector
 
## Requirements

Implement a electro-magnetic field detector and display the intensity on a 7-segment display.

## Implementation details

The intensity of the emf is captured with an antenna. The value read is constrained to be in the [0..100] interval, which will then be mapped to values in the [0..9] interval, representing the digits displayed on the 7-segment dispaly. 

## Picture of setup
![](https://github.com/StefaniaCarutasu/IntroductionToRobotics/blob/main/Homework%203/setup.jpeg)

## Video of setup
[https://youtu.be/_b5cnWRgmag](https://youtu.be/_6ShBzahU3c)
