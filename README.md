# Simple Sine Wave Generator
This is a simple sine wave generator project. It can be used as a starting point to learn JUCE libraries and audio signal processing.

Current Issues:
* No mute button
* Sine wave is generated over and over again when buffer is filled (it is not continuous, so may produce glitches)
* Time variable is not cleared after period ends (may produce overflows as it is float)

## Screenshot of this small application

![sgen](https://cloud.githubusercontent.com/assets/2100323/17632952/bc8e440e-60d3-11e6-851c-abef9c71d85e.PNG)
