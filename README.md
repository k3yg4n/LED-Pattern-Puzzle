# LED-Pattern-Puzzle

<p align="center">
  <img width="460" src="https://user-images.githubusercontent.com/91648600/167069618-28483316-2c18-49f8-8137-55a11bb99e94.jpg">
</p>

Overview
--------
The LED Pattern Puzzle is a three level memory game in which players view randomly generated light sequences using different coloured LEDs and attempt to recite them with push buttons. The player will receive corresponding feedback depending on the correctness of their input. If a user fails to recite the pattern correctly, the game is reset to level 1 with new patterns. With each level's completion, an additional term is added to the pattern. This game was developed using PlatformIO and the STM32F401RE microcontroller.

Game Details and Mechanics
---------------------------
This puzzle will wait for a player to press the start button before displaying a random colour pattern of 5 terms using different coloured LEDs. The puzzle will then wait for the player to attempt to push the coloured buttons in identical order. Every time the player passes a level, the light sequence grows one term longer. To indicate the completion of each level, the green LED will blink on and off before continuing. On the contrary, the red light will blink on and off if the player fails to repeat the sequence in the correct order and the puzzle will reset to level one with new patterns. This activity repeats for three successive level completions, after which the green light will remain glowing.

Additional Information
------------------------
Design Document can be found at: https://docs.google.com/document/d/1DWrkwa9tetPVPs-iwxpkUVQDAR5f2hEC-mwlDjDgHIQ/edit?usp=sharing

Project for ECE 198 at the University of Waterloo

Created by: Keegan Liu and Tiffany Zhang
