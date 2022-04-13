The problem:

Comparing different guitar pickups in a defined test environment is state of 
now (2022) actually impossible. Although there are various approaches to simplify 
the pickup change, which only simplifies the repetition of a test, but doesn't 
lead to a replicability. A one-to-one test requires an identical velocity dynamics 
and tone sequence. A guitarist can only approximate this but would be influenced 
in his playing by the different characters of the pickups. 
A technical setup could perhaps accomplish this physically, but the result would 
have nothing in common with normal playing practice.

The Idea:

Guitar playing is simulated with vibration generators. An amplifier excites 
these generators by the playback of an audio file. This enables an amplitude 
sequence that can always be exactly replicated.
A test setup would be just as simple, since the simulator only needs to be 
slightly larger than a guitar pickup itself.

The solution:

Just as an electric motor works like a generator in reverse principle, an 
electromagnetic pick-up can also be converted into a magnetic wave generator.  
Conventional guitar pickups can therefore be used to simulate a vibrating string. 
However, in order not to disturb the magnetic field in a test environment, the 
coils used should not have a permanent magnet in the core. Rail humbuckers in 
single coil format are best suited from a constructional point of view. 

• The permanent magnet can be removed easily.
• The blade in the core is not too thick.
• The length of the blade harmonises with the range of a string to be simulated.
• The width of the coil fits the string spacing to be simulated.

The power of a headphone amplifier is sufficient for the simmulation of the 
string vibration. For a six strings simulator it should be possible to control 
the system with a microcontroller and six i2s class D mono amplifiers in the 
low single-digit watt range.