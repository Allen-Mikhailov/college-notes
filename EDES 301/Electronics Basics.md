Everything is actually Analog, but it can be abstract it with digital
![[Electronics Basics 2025-01-16 20.06.39.excalidraw]]
There are tons of different abstraction layers so we do not have do deal with the messy stuff.
If things go wrong though you may have to have to go down layers to fix.

AC frequency in US is 60hz (50hz Europe) it if changes even by 1hz very bad things happen

When current goes around things it created electromagnetic interference.

**Voltage is relative**

### Ground
![[Electronics Basics 2025-01-16 20.19.33.excalidraw]]
Ground in circuits is relative.
Signal ground is usually based on electronics, battery
Chassis ground is usually what large systems of devices use as ground. Ex: Server Rooms
![[Electronics Basics 2025-01-16 20.21.45.excalidraw]]
Resister standards make it so that there is no resister waste with a 5% on the E24 Series as if I try to make a 10ohm and it becomes 10.6 they can mark it as an 11ohm.

Resistors in series $R_{eq}=R_1+R_2+ ...+R_n$  
- Always bigger than the largest
Resistors in series $R_{eq}=\frac{1}{R_1}+\frac{1}{R_2}+...+\frac{1}{R_n}$ 
- Always smaller than the smallest resistor

Adjustable resistors are called Potentiometers
- Often used as nobs (Hard to set exact)
![[Electronics Basics 2025-01-16 20.37.22.excalidraw]]

### Capacitors
Capacitors can store energy and release it really fast. Allows us to use energy up really fast by storing it for later. Measured in Farads
Polarized vs Non-Polarized. Polarized Capacitors can only accept charge in one direction. They can blow up very easily
Can also be used to filter things
![[Electronics Basics 2025-01-16 20.41.39.excalidraw]]

### Inductors
How we convert voltages in power electronics

### Diodes 
Current flows in the direction of the Arrow (Conventional Current)
- LEDs are diodes (Light Emitting Diodes)
![[Electronics Basics 2025-01-16 20.47.29.excalidraw]]

### Transistors
On off Switches that use power
![[Electronics Basics 2025-01-16 20.48.42.excalidraw]]

$V=IR$
$P=VI=\frac{V^2}{R}=I^2R$
Power is dissipated in the form of heat. 60 Watt PC is 60 Watts converted to heat which means they get really hot

### RC Filter
Low pass filter with RC time constant
![[Electronics Basics 2025-01-16 21.02.45.excalidraw]]