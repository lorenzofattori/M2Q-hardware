# Control your Chamsys console via MIDI

![M2Q Hardware](https://github.com/lorenzofattori/M2Q-hardware/raw/main/images/20210702_114011.jpg)

M2Q is A powerful MIDI to Chamsys Remote converter designed to trigger playbacks, cue stacks and synchronize tap-to tempo using MIDI Messages

It has been engineerd by me, based on an idea and concept of Manuel Rodriguez. Manuel is a professional light designer who used this little box in his amazing shows, touring all over the world! You can find more about his amazing work [here](http://www.deepred.tv/).

M2Q is available at my [Tindie Store](https://www.tindie.com/products/23305/)

Store update July 2021: Very limited quantity available at the moment.

## Check all the documentation pages:

[Features](./features.md)

[Quick Start Guide](./quickstart.md)

[Configuration Webpage](./configuration.md)

[FAQs](./faq.md)

[Videos](./videos.md)

## How It Works

- M2Q has a USB port, which acts as a USB-MIDI Interface, just connect it to any PC or MAC and it will appear as a MIDI device.
- There is also an Ethernet port, which is connectected to the Chamsys console (or software)
- M2Q Listens to MIDI Note, MIDI ControlChange and MIDI Clock messages being sent to the MIDI interface.
- When one of these messages it's received, it gets processed and a Chamsys Remote message is sent out to the console.
- Works with both Chamsys consoles and MagicQ PC, software needs to be unlocked and only the first 10 playbacks are available in the PC version.
- Just plug your midi interface, select M2Q in your MIDI software, and start sending MIDI messages!



## Main Features

### Triggering Playbacks
Triggering Playbacks is used for remotely activate and switch cues inside a playback of MagicQ. This can be useful for real-time cue triggering without having to use Timecode.

### Changing Playback Level
Changing Playback Level is used for remotely change level of a playback of MagicQ like moving the console faders Up/Down. This can be useful for real-time fades without having to use Timecode. Since the behaviour of the playback level can be changed in MagicQ, it is possible to use it for remotely changing Intensity, speed, size, etc.

### Triggering The Stack Store
Triggering The Stack Store is used for remotely activate/deactivate cue stacks inside the Stack Store of MagicQ. This can be useful for real-time cue flashing or activating chases having to use Timecode.

### Tap2Tempo Trigger
Tap2Tempo Trigger is used to synchronize a MIDI clock signal to the internal console global tempo (BPM) by remotely tap to the GO button of MagicQ. This can be useful for synchronizing Chamsys effects to MIDI Clock.

For more details, check the [Features page](./features.md) 





