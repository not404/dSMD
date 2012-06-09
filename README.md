dSMD
====

dSMD - dSpin Stepper Motor Driver, a triple axis stepper motor driver board based on the L6470 chip.

The L6470 is a very advanced stepper motor driver. It can be controlled accurately though an SPI interface. Through this interface acceleration, decceleration, maximum speed and minimum speed can be programmed in. This then allows the user to simple command the chip to move the motor in a specific direction by n number of steps. Alternatively a target speed may be set or a target position. The aim is to reduce the overhead on the host processor for motion control.

This board puts 3 of these fantastic chips together on a single PCB. This should be ideal for a CNC or 3D printer with steppers requiring up to 3 Amps each.

More information on the L6470 can be found here: http://www.st.com/internet/analog/product/248592.jsp