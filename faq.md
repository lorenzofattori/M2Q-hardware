# FAQs

### Does M2Q work with any Chamsys device?
M2Q works on any Chamsys console which accepts the Chamsys Remote Protocol commands via UDP messages, more info can be found [here](https://secure.chamsys.co.uk/help/documentation/magicq/udp.html)
Currently, it has been tested with the following Consoles:

- MQ60
- MQ80
- MQ500
- MagicQ PC (unlocked)


### Are there any limitations when using M2Q with MagicQ software?
Yes, first of all you need to unlock the software (ouf of demo mode) by connecting chamsys hardware to the PC/MAC. More info [here](https://secure.chamsys.co.uk/help/documentation/magicq/pc.html#_magicq_pc_mac_restrictions)
Then, when using MagicQ software, only the first 10 playbacks can be controlled remotely, so M2Q will only control those 10 playbacks and wing mode will not work. Morer info [here](https://secure.chamsys.co.uk/help/documentation/magicq/rpc.html)


### I want control Chamsys with an external MIDI device, can I do it with M2Q?
Yes, M2Q accepts any standard MIDI message, no matter if it's software or hardware. In order to do that, you need a software that "bridges" the connection between the external MIDI device and M2Q. **You can't connect M2Q USB cable directly to a MIDI device**
In Mac OSX, just use the built-in MIDI Studion to route the MIDI messages between the devices.
On Windows, you can use [LoopMIDI](https://www.tobias-erichsen.de/software/loopmidi.html).


### Is M2Q software open source?
No, the software in the M2Q microcontroller is not open soruce. I spent hundreds of hours working and refining the project and I never got paid for it.
By selling M2Q hardware on [Tindie](https://www.tindie.com/stores/lorenzofattori/) I hope I will make various light designers happy and be able to repay a bit the effort I put in this project.
If you are looking for an open source version and you know a bit of Python, you can have a look at the [Python version of M2Q](https://github.com/lorenzofattori/M2Q-python).


### I need a modification in the software, is it possible?
We designed M2Q in order to be as modular as possible, and with modern MIDI tools you should be able to use it in any scenario.
However, if you need a special modification for your project, you can contact me and I can see if it's possible to do that.


### I need a custom MIDI / DMX / Artnet / lighting related product, can you create it for me?
While I love the lighting world, I'm not a lighting freelancer anymore and I'm employed in another sector. These custom projects are awesome and I would love to do them as my daily job, but unfortunately I'm limited to my spare time.
Contact me with our idea and I will consider it!
