# Sands Of Time

## Project Description

### Overview

### Mechanical

### Electrical

### Software

[Parallax Propeller 2 Documentation](https://www.parallax.com/propeller-2/documentation/)

Cog responsibilities:
- Main: Watchdog and timing, coordinate other cogs
- ReadClock: Read the RTC
- ReadHourglassEncoders: Read absolute encoders on the hourglasses
- ReadArmEncoder: Read the quadrature encoder on the arm
- HourHand: Move the main arm 
- LEDs: Control the LEDs


## Things to remember to prevent the wrath of Garner

1. Fuses on everything
2. LEDs on power supply inputs
3. Ground on bottom by convention
4. Do as much as possible in CAD first

## Future Work:

### Features

- Motor stall prevention: back off hourglass if supposed to be moving and no encoder change detected
- PCB instead of perfboard

### Problems

1. Homing sensor wobbles
2. Sometimes we blow a fuse on the LEDs and IDK why
3. Have to hard-code positions
4. 

### Solutions
1. Better back mounting plate for motor and quadrature encoder 
2. Better fitting gear on quadrature shaft wobbles as it spins
- Mount power supplies better
- Consistent LED wiring
- Better Dupont ribbon cables for encoders and LEDs ( Or heatshrink them)
- Replace hour 5 encoder
