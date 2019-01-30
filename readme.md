# propshield2OSC

Code that was running on shoe demo for holoplot (lift)

needs router credentials and a valid ip for sending OSC to a pd patch

OSC message format is /motion/<pitch> <yaw> <roll>
  
unpackable in pd with [route motion] into [unpack f f f]
