# Atari-Dragonfear
Dragonfear Game by Jerry Young which he is converting to Atari from other platforms.

---

The game is Work In Progress by Jerry Young.

Jerry Young/"Pitfall Jerry" YouTube channel is here:  https://www.youtube.com/channel/UCLC48m8whLqS23CEt5ImQBg

---

Coding Dragonfear on the Atari 8-bit Home Computer YouTube streaming episodes:

Episode 294:  https://youtu.be/fKUFz4vzWK0

Episode 295:  https://youtu.be/dTgWKNRJXzA

Episode 296:  https://youtu.be/e03FYQs5KLY

---

"ORIGINAL" in the file name means this is a file that was acquired before any of my personal hacking.  The "EDIT" files are the resulting mess I make. 

**2020-07-14** - Modified to replace the numeric array with a string.  This allows redrawing the screen by using one PRINT directly to the screen instead of looping through the numeric array and converting each element to a character.

**2020-07-27** - Added Routine at 2100 to provide joystick input instead of keyboard.   The bulk of the remaining program is unchanged.  Only the INPUT Z$ is changed to GOSUB to the joystick reading routine.  The Joystick routine populates Z$ with the character that would have been typed from the keyboard. 

**2020-07-28** - Derp!  The string initialization in line 2019 was wrong.  

THIS -> 2019 A$=" ":A$(2)=A$:REM BLANK THE STRING

SHOULD BE-> 2019 A$=" ":**A$(300)=" "**:A$(2)=A$:REM BLANK THE STRING

Updated the 07-27 version to 07-28 for this problem.

---
