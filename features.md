### Triggering Playbacks

Triggering Playbacks is used for remotely activate and switch cues inside a playback of MagicQ. This can be useful for real-time cue triggering without having to use Timecode.

- When a **Note ON** message (note X of MIDI Channel Y) is sent, M2Q will convert it in trigger Cue X of Playback Y.
- Works with Playback 1-15 an corresponds of the first 15 Playbacks of the Console (Note: M2Q PC is limited to the first 10 Playbacks).
- Up to 126 Cues for every playback can be triggered.

### Changing Playback Level

Changing Playback Level is used for remotely change level of a playback of MagicQ like moving the console faders Up/Down. This can be useful for real-time fades without having to use Timecode.
Since the behaviour of the playback level can be changed in MagicQ, it is possible to use it for remotely changing Intensity, speed, size, etc.

- When you send a **ControlChange** message with value X (Controller 1 of MIDI Channel Y), M2Q will convert it in change playback Y level to X value (0-100%).
- Works with Playback 1-15 an corresponds of the first 15 Playbacks of the Console (Note: M2Q PC is limited to the first 10 Playbacks).
- Value from 0 to 100 corresponds to playback level 0 to 100%, from 101 to 126 is kept to 100%.

### Triggering The Stack Store

Triggering The Stack Store is used for remotely activate/deactivate cue stacks inside the Stack Store of MagicQ. This can be useful for real-time cue flashing or activating chases having to use Timecode.

- When you send a **Note ON** message on note X of MIDI Channel 16, M2Q will convert it in activate Cue Stack X of the Stack Store.
- When you send a **Note OFF** message on note X of MIDI Channel 16, M2Q will convert it in deactivate Cue Stack X of the Stack Store.
- Up to 126 Cues Stacks can be triggered.

### Tap2Tempo Trigger

Tap2Tempo Trigger is used to synchronize a MIDI clock signal to the internal console global tempo (BPM) by remotely tap to the GO button of MagicQ. This can be useful for synchronizing Chamsys effects to MIDI Clock.

- When a **MIDI clock** message is received, a Chamsys message for the remote trigger is sent out.
- The Global Tempo will now follow the MIDI Clock signal (same BPM)
- Note: The remote trigger needs to be set up as Tap to time sel PB.

### Wing Mode

When this option is selected, M2Q will trigger the playbacks from 11 to 25 instead of 1 to 25, in this way you can still use your first 10 playbacks manually and have the "automated" triggering on the first wing playbacks.
