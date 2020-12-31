DigitalPin.h
An intuitive way of addressing GPIO pins.

 DigitalPin Class functions:
     beginOUT(): Initialises pin as output
     beginIN():  Initialises pin as input
     beginPULLUP(): Initialises pin with a pullup resistance
     on():          Set pin on
     off():         Set pin off
     level(int val):       Set PWM value (0 - 255)
     status():      Returns boolean status of pin set by on()/off()
     readState():   Returns Boolean state set by program
     pulseInHigh(): returns length of HIGH pulse
     pulseInLow():  returns legth of LOW pulse
     pulseInHighTOut(unsigned long timeOut): returns length of HIGH pulse with time-out
     pulseInLowTOut((unsigned long timeOut):  returns length of LOW pulse with time-out
                           