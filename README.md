# C64-Keyboard-Controlled-Kernal-Switch 6526

This project is based on the C64 Keyboard Controlled Kernal Switch Rev. 1.0 from Sven Petersen  (github: svenpetersen1965). For additional informations take a look at Sven Petersens github resipository. 

The original kernal switch ist directly connected to the C64 keyboard connector. In my C64 (bread box) with board Assy 250407 the Kernal Switch lies on the fastening screw and other components with the risk of an electrical connection. So I developed an alternative.
The kernal switch 6526 is an intermediate socket for the 6526 on U1.

Advantage:
- better mechanical stability
- SMD soldering pads for hand soldering

Disadvantage:
- additional line for querying the restore button
- if the 6526 is not socketed, it must be unsoldered


Rev 1.0: Design based on Sven Petersens C64 Keyboard Controlled Kernal Switch (ATmega with external clock at 16 MHz)

Rev 2.0: Cost-reduced Design (ATmega with internal clock at 8 MHz)
