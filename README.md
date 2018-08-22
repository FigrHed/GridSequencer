
GridSequencer is a sequencer largely based on Stretta's Gridlab Sequencer 16p and Plane.

It works immediately with a 256 grid as a 14*16 step sequencer Max for Live MIDI effect but has a few nice features that make it super quick and intuitive to write music in Ableton Live.

The First Row is a playhead with no touch functionality at this time.


The next 14 rows are the sequencer space. 
(Each button acts as a toggle and a light on represents a note. When the playhead reaches the end, It returns to the start and continues playing as a loop.)

The notes are by default chromatically ascending from C1 but can be quickly changed with the mouse or with a midi controller.


The bottom row is left over to use as controls for navigation/editing/various functions you may use while making loops.

The button on the far right shall be called "Select", and the 5th button from the left shall be called "Alt".

The four buttons closest to the left are for navigating:
The first button navigates the first section (of 16 whichever unit we are counting in)
the second button represents the second section, and so on.

To reach the fifth section or further you must hold down Alt.

button 1 = begins at 0

button 2 = begins at 16

button 3 = begins at 32

button 4 = begins at 48

alt + button 1 = begins at 64

alt + button 2 = begins at 80

alt + button 3 = begins at 96

alt + button 4 = begins at 112

At the moment, the length is capped at 128 but you are welcome to change this.



While holding down shift, these same four button alter the length.

shift + button 1 = 16  divisions

shift + button 2 = 32  divisions

shift + button 3 = 64  divisions

shift + button 4 = 128 divisions

The looping sections then begin flashing while the selected section remains solid.

The loop length can also be changed with the number box in the device window, which can be easily mapped to a MIDI controller or arc.


Next we have the three modes, select mode, pitch mode and velocity mode.

SELECT MODE

Holding the bottom right button("shift") puts the device into select mode and the selected row will be highlighted. Press any button on the row while still holding shift to change the selected row.
Any MIDI note to the channel will change the note.
You can also change the notes associated with the rows by clicking the boxes in the device.


PITCH MODE (DEFAULT)

Holding select and the 13th button will put the device in pitch editing mode (which is the mode the device begins in) 


VELOCITY MODE
The 14th button will put it in Velocity editing mode, where  you can change the velocity of the notes on the selected row.
(again, you can change the selected row by holding select)

The default is the 10th row which I think is about 100.



Now lastly we have two convenience functions:

While holding the the select key, pressing the 9th button will create a new MIDI clip in the track the device is on out of the loop created on the grid and then trigger it. While the track has a clip playing, it will have its own MIDI disabled, this means you can't change the notes with MIDI either.

Pressing the 9th button with the shift AND alt buttons held will clear the current loop in the device.
It may be a bad idea to have the same button do those two divergent things, but I deliberately made it so that you need to use two hands to clear your work so its hard to accidentally do it.
If it is comfusing please let me know (by raising or adding to an issue).

~FigrHed
