# Force-open-Bitalino
Use Bitalino sensors without core

https://bitalino.com/products/plugged-kit-bt

Ad8232 *2 Single-Lead, Heart Rate Monitor Front End

1333A TI 51K AEPE   +    BQZ TI K 483Y  for eeg *1

Accelerometer: analog + lpv324 r2r opamp



https://github.com/BITalinoWorld/arduino-api
No arduino c code. Only assembly C. 
→ reverse engineer and redo code

Rev ecg related modules


Left i1 to a1
Empty
2chip
A direct
Ad
Ad

Right
Empty
Empty
Button
Buzzer
Acc sen(on analog!!)


2chip 
AVCC 3.2v
Ref 1.6v
Analog out


Same voltage for AD but only receive voltage on port 4 and 5

Same voltage for direct A/ diff opamp

Design need: 
2 way ADC, 1 for acc, 1 for choice of ecg
Some kind of wireless data stream

Thats it.


Rev onboard connection or make my own. 
Need FTDI breakout, reset management? 

Plan:
Connect ftdi and test upload. If work, good. Else if brick or doesn’t upload, make own. 
11/27



12/2/2020
BT module is wired to program serial smh. Not going to bother reusing original atmega328

