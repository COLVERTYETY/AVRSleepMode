# avrsleepmode
exemple code on how to use sleep mode on an atmega328p in avr assembly.
This code was written as part of a 1st year course on mcu architecture.
If any avrfreaks would happen to pass by I am open to all critiscisme an pull requests.

Two interrupts are used to either send the mcu to sleepmode(INTV1) or to wake it up(INTV0).
the number of times the mcu has been waken up are counted in the "count" register 
current sleemode is PowerDown.
for reference other sleep modes are:
        000:Idle Mode
        001:ADC noise Reduction Mode
        010:PowerDown Mode
        011:Standby
        111:Extended Standby
