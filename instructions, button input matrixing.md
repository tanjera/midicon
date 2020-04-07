To maximize inputs and use an input array, see the following steps and references:


NOTE: These solutions REQUIRE one of several methods for implementation:
1) The use of diodes for EACH button in a matrix (easier)
OR
2) The use of multiplexer chips (harder, needs interpretation and introduces delay)


A VERY good tutorial of using a ButtonMatrix via Arduino Leonardo and diodes:
https://www.digikey.com/en/maker/projects/agm-summer-break-edition-raspberry-pi-midi-controller-synthesizer/45f94d1c75644494aaf7dda60e9b8693
includes circuit diagram, libraries used, code, and also linking to R-Pi for synthesizing


https://github.com/tttapa/MIDI_controller
has support for ButtonMatrix:
"This allows you to use a very large number of buttons with only a limited number of IO pins."

