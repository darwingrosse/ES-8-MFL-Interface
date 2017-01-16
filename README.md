# **ES-8 MFL Interface**

This Max For Live device gives you a direct, low-maintenance interface between
your Ableton Live track and your modular. It is dependent on using the
Expert Sleepers' ES-8 interface, and assumes that the power supply in your
modular is providing stable power (which determines if the voltage scaling of
the ES-8's output is properly scaled).

## Setup

1. Install somewhere on the computer you are using with Ableton Live/MFL.
2. Place the ES-8 Interface device on a MIDI track.
3. Select a stereo pair of outputs for your track.
4. Play MIDI through the track!

You have to use a stereo pair for the output because one output (the first) is
the scaled note value, while the other (the second) is the gate of the output.

## In Use

Pretty simple, mainly due to the powerful and stable nature of the ES-8. One
thing: with the 'mono mode' function off, it will pass full polyphonic output
to the modular. But this is seldom useful; instead, turn mono mode to 'on' and
it will properly switch notes without note-off problems.

Generally speaking, unless you have some sort of switching function in place,
you probably want mono mode switched 'on' (it is on by default).

## Future Plans

- I hope to implement pitch bending and velocity in the near future.
- At some point I will implement legato slewing, but not right now...

## History

2017-01-16 : Initial Release
