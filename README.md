# Weighted Probability Sequencer

*Max 8.3*

This Max for Live Device creates MIDI-notes according to weighted probability tables for the following parameters: note, octave, velocity and note-length.
The x-axis represents the note(parameters) and the y-axis the probability of it's occurrence. The bottom of the y-axis represents the probability of 0, which means this property will never be set.
The interface consists of four screens, which can be switched using the buttons to the bottom right. 
Each screen shows the note value-control on the bottom left, determining how fast the notes are played.
There are also presets for scales provided as .txt-files which can be accessed in the note-interface.

The controls are: <br/>
*note-interface*
**table of notes** <br/>
**root**: set the root note of a scale preset <br/>
**scale**: set a scale preset <br/>
**random**: randomize the table <br/>
![note](/pictures/WP_Sequencer_1.png) <br/>
<br/>
*octave-interface* <br/>
**table of octaves** <br/>
**random**: randomize the table <br/>
![note](/pictures/WP_Sequencer_2.png) <br/>
<br/>
*velocity-interface* <br/>
**table of velocities** (in 10 steps) <br/>
**random**: randomize the table <br/>
![note](/pictures/WP_Sequencer_3.png) <br/>
<br/>
*note-length-interface*<br/>
**table of note-lengths** <br/>
**random**: randomize the table <br/>
![note](/pictures/WP_Sequencer_4.png) <br/>
<br/>

It is inspired by this tutorial by [Andrew Robinson](https://www.youtube.com/watch?v=AkYRhaD5xoc).
