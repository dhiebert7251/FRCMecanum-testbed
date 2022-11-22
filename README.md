# FRCMecanum-testbed
basic mecanum drive code with additional code testing

## Contents

- [Current Hardware Setup](#current-hardware-setup)
  - Drivetrain
  - Shooter
- [Upgraded Hardware Setup](#upgraded-hardware-setup)
  - Drivetrain
  - Shooter
- [Things to try](#things-to-try)

## Current Hardware Setup 

Subsystem | Motor(s) | Controller(s) | Sensors
:-:|:-:|:-:|:-:
Drivetrain | 4 x CIM | 4 x Spark | none
Shooter | 2 x ? | 2 x Spark | none

### Drivetrain
Location | Motor | Controller | PWM/CAN 
:-:|:-:|:-:|:-:|
Front Left Drive | CIM | Spark | PWM 1 
Front Right Drive | CIM | Spark | PWM 2 
Rear Left Drive | CIM | Spark | PWM 3 
Rear Right Drive | CIM | Spark | PWM 4 

###  Shooter
Location | Motor | Controller | PWM/CAN | Sensors
:-:|:-:|:-:|:-:|:-:
Shooter Top | ? | Spark | PWM 5 | None
Shooter Bottom | ? | Spark | PWM 6 | None

## ** Upgraded Hardware Setup **

Subsystem | Motor(s) | Controller(s) | Sensors
:-:|:-:|:-:|:-:
Drivetrain | 4 x NEO | 4 x Spark MAX | NEO Hall Effect Encoders
Shooter | 2 x ? | 2 x Spark | none

### DRIVETRAIN
Location | Motor | Controller | PWM/CAN 
:-:|:-:|:-:|:-:
Front Left Drive | NEO | SparkMAX | CAN 21
Front Right Drive | NEO | SparkMAX | CAN 22 
Rear Left Drive | NEO | SparkMAX | CAN 23
Rear Right Drive | NEO | SparkMAX | CAN 24 
 | | | 
Front Left Encoder | | | CAN 31
Front Right Encoder | | | CAN 32
Rear Left Encoder | | | CAN 33
Rear Right Encoder | | | CAN 34


###  SHOOTER
Location | Motor | Controller | PWM/CAN | Sensors
:-:|:-:|:-:|:-:|:-:
Shooter Top | ? | Spark | PWM 5 | None
Shooter Bottom | ? | Spark | PWM 6 | None

