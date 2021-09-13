# CBM-Tape-Pi-PCB
# Preliminary Release of Rev.2
This is the PCB, that I have created for <a href="https://github.com/RhinoDevel/cbmtapepi">RhinoDevel's CBM Tape Pi</a>.

It is <b>not yet tested</b> and this is only a <b>preliminary</b> release!

<img src="https://github.com/svenpetersen1965/CBM-Tape-Pi-PCB/blob/main/Rev.%202/pictures/9504_CBMTapePi_PCB.JPG" width="300" alt="CBM Tape Pi PCB v2">

The PCB has an option for a barrel connector Power Supply. Also, for possible future software development, a rotary encode and an I²C OLED-Display can be connected. This is not yet supported.

<img src="https://github.com/svenpetersen1965/CBM-Tape-Pi-PCB/blob/main/Rev.%202/pictures/9505_CBMTapePi_Rot_Disp.JPG" width="300" alt="CBM Tape Pi PCB complete">

Debugging result so far:

There is a screw up with signals <b>BCM11</b>, it shoudl be connected to the collector of Q4, but the signal name is screwed up. A botch wire is required between the collector of Q4/R8 and Pin 23/BCM11 of the Raspberry Pi.

<img src="https://github.com/svenpetersen1965/CBM-Tape-Pi-PCB/blob/main/Rev.%202/pictures/9635_BCM11_botch_wire.JPG" width="300" alt="CBM Tape Pi PCB v2">
