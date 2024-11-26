# RP2040-Digital-Rotary-Encoder
RP2040 Rotary Encoder for precise &amp; fast step counting for dials

![image](https://github.com/user-attachments/assets/80a4bb1b-9869-4554-8449-207aaf8de772)


You create a rotary encoder by first creating a RotaryEncoder object
RotaryEncoder encoder1;

Then it's:
encoder1.attach(DTpin, CLKpin, SWpin);
the SWpin is unused

to get the value from the encoder simply use:
encoder1.getCounter()
