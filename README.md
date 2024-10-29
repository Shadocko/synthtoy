# Introduction

Synthtoy is a tiny webapp, which lets one code a software audio synthesizer loop using minimalistic JavaScript and play with it using either a computer keyboard or MIDI devices.

The user only has to code the body of a function returning one audio sample, with levels for the left and right channels in range [-1;1] as a two-values array.
The app is in charge of calling the function in a loop for every note that is being played, working as a polyphonic synthesizer.

It is also possible to play multiple synthesizers, each responding to only a part of the keyboard or MIDI device, thanks to input mappings configuration.

This app was coded for fun. Don't expect too much of it, but don't hesitate to [open a ticket](https://github.com/Shadocko/synthtoy/issues) if you encounter any issues.
Enjoy ;-)

# Try it out

Just point your browser to https://shadocko.github.io/synthtoy/

# License

Synthtoy is released under the terms of the [GNU GENERAL PUBLIC LICENSE v3](https://www.gnu.org/licenses/gpl-3.0.en.html).
