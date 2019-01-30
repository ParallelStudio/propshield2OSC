# propshield2OSC

Code that was running on shoe demo for holoplot (lift)

requires a teensy wired to a winc1500 and a propshield

propshield is using default pins
winc1500 is using 10,6,5 // CS, irq, rst

needs router credentials and a valid ip for sending OSC to a pd patch

OSC message format is /motion/*pitch* *yaw* *roll*
on port 9999
  
unpackable in pd with [route motion] into [unpack f f f]
