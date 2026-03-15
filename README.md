# NE555-Delay-Timer-1.5-Minute-Delayed-LED-Activation-
NE555 Delay Timer – 1.5 Minute Delayed LED Activation 
This circuit uses the classic NE555 Timer IC configured in monostable (delay) mode to create a delay of approximately 1 minute and 30 seconds before turning on an LED.

When the circuit is powered by the 9 V battery, the timing capacitor C2 (100 µF) begins charging through R1 (100 kΩ). During this charging period, the output of the 555 timer remains LOW, so the LED is OFF.

The delay time is determined by the standard 555 monostable timing equation:
T = 1.1RC
