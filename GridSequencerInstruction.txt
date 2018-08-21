
GridSequencer is a sequencer largely based on Stretta's Gridlab Sequencer 16p and Plane.

It works immediately with a 256 grid as a 14*16 step sequencer Max for Live MIDI effect but has a few nice features that make it super quick and intuitive to write music in Ableton Live.

The First Row is a playhead with no touch functionality at this time.

The next 14 rows are the sequencer space. Each button acts as a toggle and a light on represents a note. When the playhead reaches the end, It returns to the start and continues playing as a loop.

The notes are by default chromatically ascending from C1 but can be quickly changed with the mouse or with a midi controller.
Click the box next to the note that represents the row you would like to change and send MIDI to the channel to change the note.
Pressing the bottom right button("shift") puts the device into select mode and the selected row will be highlighted. Press any button on the row while still holding shift to change the selected row.

The length can be changed with the length number box in the device, and the offset can be changed to reach the parts of the loop that are not visible.
This enables a greater degree of freedom and fluidity when making loops.
A MIDI controller (or an arc) can be mapped to either of these but for convenience and dexterity, the bottom row acts as a editting/navigation control.

The far right button on the bottom row shall be called "Shift", and the 5th button from the left shall be call "Alt.

The four buttons closest to the left are for navigating.
The first button represents the first section (16 of whichever unit we are counting in)
the second button represents the second and so on.

While holding down shift, these same four button alter the length.

shift + button 1 = 16  divisions
shift + button 2 = 32  divisions
shift + button 3 = 64  divisions
shift + button 4 = 128 divisions

The appropriate amount of button then begin flashing apart from the selected section which remains solid.

If you want to navigate to a section after the first four, you must hold down alt (the fifth button from the left)

button 1 = begins at 0
button 2 = begins at 16
button 3 = begins at 32
button 4 = begins at 48

alt + button 1 = begins at 64
alt + button 2 = begins at 80
alt + button 3 = begins at 96
alt + button 4 = begins at 112

At the moment, the length is capped at 128 but you are welcome to change this.

Next we have the two modes, pitch mode and velocity mode.

While holding shift, the 13th button will put the device in pitch editting mode (where it opens at) and the 14th button will put it in Velocity editing mode, where the selected row (again, changed in select mode by holding shift) can have each event's velocity changed.
The default is the 10th row which I think is about 100.

Now lastly we have two convenience functions:

While holding the the shift key, pressing the 9th button will create a new MIDI clip in the track the device is on out of the loop created on the grid and then trigger it. While the track has a clip playing, it will have its own MIDI disabled, this means you can't change the notes with MIDI either.

Pressing the 9th button with the shift AND alt buttons held will clear the current loop in the device.
It may be a bad idea to have the same button do those two divergent things, but I deliberately made it so that you need to use two hands to clear your work so its hard to accidentally do it.
If it is comfusing please let me know (by raising or adding to an issue).

~FigrHed
