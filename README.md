# RPSLSp
An extended version of the classic rock-paper-scissors game using arduino

## Overview
This game is inspired from the sitcom The Big Bang Theory. You have 5 buttons to choose the gesture. The computer randomly chooses a gesture. First to score 4 points wins.  
Rules : https://www.youtube.com/watch?v=pIpmITBocfM&ab_channel=TBS

## How it works
There are 5 push buttons each corresponding to a getsure. There is an indicator LED prompting the player to choose a gesture. If the user fails to choose a gesture within limited time, computer automatically gets a point. Onve the user has selected a gesture, the computer randomly picks a gesture. The computer's choice is indicated to the user by a set of 5 LEDs each corresponding to a gesture. The score is shown in binary numbers to reduce the number of required LEDs. Two LEDs for computer and another two LEDs for the player displays the score. When one party reaches 4 points the corresponding pair of LEDs flash to indicate the winner. There is also a buzzer to make the game feel responsive and to indicate the outcome of the rounds.

## Tools used
The game was coded using PyFirmata library in Python.  
An arduino UNO board was used as the micro-controller.  
Push buttons, LEDs, a piezo buzzer were used with a breadboard as the interface. 


You can find the source code, the circuit diagram and a video demonstration in this repository as a zip file.





