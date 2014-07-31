PIRMotionDetector
=================

This is a project based on the motion sensor extraced for the very low cost Ikea Oleby wardrobe light and the Dual OpAmp LM358 driven from a 3.3v powersupply.

It's purpose is to make use of the PIR sensor with only a few components to ease it's use with a microcontroller like the arduino/atmega.
  * The sensor PIR D203S can be bought here: http://www.futurlec.com/PIR_D203S.shtml
  * D203S User manual: http://roboeq.com/PDF/0404011.pdf
  * LM358 Manual: http://www.ti.com/lit/ds/symlink/lm158-n.pdf
The D203S manual has an example using the LM324, but it includes a lot of components we might not need on lower voltages like 3.3v.
  * Project package with Eagle schematics and Arduino Teensy Sketch
