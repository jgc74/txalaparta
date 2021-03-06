Txalaparta. by www.ixi-audio.net
info@ixi-audio.net
license: GNU GPL
www.ixi-audio.net/txalaparta

Description
An app to research the txalaparta rhythms by implementing them into a digital system. It is part of the Doctoral research by Enrike Hurtado. 
http://www.ixi-audio.net/txalaparta

what is the txalaparta? >> https://en.wikipedia.org/wiki/Txalaparta

Standalone apps here
www.ixi-audio.net/txalaparta/digital

There are two apps :

- Autotxalaparta : a program that generates txalaparta-like rhythms that can be controlled from a GUI

- Interactive txalaparta : a program that listens to the input (via mic) of a single txalaparta player and responds according to the rules of the txalaparta playing. It learns from the input and responds according to the patterns and style learnt from the player.

The Interactive txalaparta has a system to sample several hits from your own txalaparta to later use those samples to answer to your play. It also has two calibration systems, the first is rhythmical and allows the system to filter out echoes or background noise that might interfiere with the rhythms in the mic. The second system is timbrical and allows the program to differentiate each plank. That way it can know in which plank each the player hits.

Timbrical calibration (Chroma Manager):  Press first the grey button labelled "C" in order to clear the calibration data first. Then press button 1 (the button goes red) and hit the plank you want to associate with that number (button goes black). Repeat for each plank with a different number. If the system cannot always differentiate them try introducing a hit in a different location. You might want to use a voice microphone, it can be a very cheap and work properly. Laptop builtin mics are sometimes too sentitive.

There are some videos here explaining how to use the calibration systems. http://www.ixi-audio.net/txalaparta


* How to run:
Standalone apps here www.ixi-audio.net/txalaparta/digital

Running the source code: 
Both programs are created with Supercollider. You need to install Supercollider to run them. Supercollider is free software. It also requieres Chromagram and WAmp extensions, which are part of the SC3plugins for Supercollider.
http://doc.sccode.org/Classes/Chromagram.html
http://doc.sccode.org/Classes/WAmp.html

- open with Supercollider the digital_txalaparta.scd file
- select all the text in the file
- hit CTRL + Return, or Apple + Return on Mac


* How to use:
Some video demos explaning the functionality can be found here
http://www.ixi-audio.net/txalaparta


* THANKS TO
- Elhuyar
- Euskal Herriko Unibersitatea / University of the Basque Country
- University of Sussex
- Rainer Schuetz and the Supercollider list



