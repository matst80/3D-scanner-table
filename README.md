# 3D-scanner-table
Shared space to improve design of the 3D scanner table

## This repo

src/ will hold the code
plans/ will hold the plans for construction and cables

## Plans

ESP-8266 to control the steppermotor and allow it to be controlled by phone or other hardware/software

NEMA Steppermotor, drive the shaft and the pulleys that finally rotate the table in accurate steps

Case made from 3D models and then prited och laser sliced

Drivetrain/pulleys made by 3d printed gears, bicycle gears or belts

Software will be Arduino compatible and use libraries for steppermotor driving and networking.

## Solve
* Drive train type and bearings, then calculate steps number of degrees / step (steppermotor)
    * Bearings
    * Axles
    * Gears / Pullys
    * Tensioning
    * (Low play tolerance)

* Create stable rotating disk, with axle.

* Create 3d models for casing.

* Develop software for driving stepper and convert to degrees and complete turns on the scanner surface.

* Soldering the stepper driver to the board and powersupply
    * Powersupply suggestions 12v DC and stepdown for ESP to 3.3v

* Assemble meckanism

* Fine tune

* Assemble into the casing.

* Scan something

* Redo evertying thats not working properly :)


## Skills to learn / teach

* Soldering

* 3D modelling

* Coding (Arduino/C++)

* Laser cutting

* Lathe (for axles)

* Mechanics

* Versioncontrol (GIT)

* Circuitboard making (when working)


[Hardware specifications link](hardware/README.md)

[3D models specifications link](models/README.md)

[Code for ESP](src/stepperdriver.ino)