# M2Q - Control your Chamsys console via MIDI

M2Q is A powerful MIDI to Chamsys Remote converter designed to trigger playbacks, cue stacks and synchronize tap-to tempo using MIDI Messages

It has been designed by me, based on an idea of Manuel Rodriguez. Manuel is a professional light designer who used this little box in his amazing shows, touring all over the world!

## How It Works

- M2Q has a USB port, which acts as a USB-MIDI Interface, just connect it to any PC or MAC and it will appear as a MIDI device.
- There is also an Ethernet port, which is connectected to the Chamsys console (or software)
- M2Q Listens to MIDI Note, MIDI ControlChange and MIDI Clock messages being sent to the MIDI interface.
- When one of these messages it's received, it gets processed and a Chamsys Remote message is sent out to the console.
- Works with both Chamsys consoles and MagicQ PC, software needs to be unlocked and only the first 10 playbacks are available in the PC version.
- Just plug your midi interface, select it and start sending MIDI messages!


## Main Features

### Triggering Playbacks
Triggering Playbacks is used for remotely activate and switch cues inside a playback of MagicQ. This can be useful for real-time cue triggering without having to use Timecode.

### Changing Playback Level
Changing Playback Level is used for remotely change level of a playback of MagicQ like moving the console faders Up/Down. This can be useful for real-time fades without having to use Timecode. Since the behaviour of the playback level can be changed in MagicQ, it is possible to use it for remotely changing Intensity, speed, size, etc.

### Triggering The Stack Store
Triggering The Stack Store is used for remotely activate/deactivate cue stacks inside the Stack Store of MagicQ. This can be useful for real-time cue flashing or activating chases having to use Timecode.

### Tap2Tempo Trigger
Tap2Tempo Trigger is used to synchronize a MIDI clock signal to the internal console global tempo (BPM) by remotely tap to the GO button of MagicQ. This can be useful for synchronizing Chamsys effects to MIDI Clock.





## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/lorenzofattori/M2Q-hardware/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lorenzofattori/M2Q-hardware/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
