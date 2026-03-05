Project Description – Transistor Guitar Distortion Pedal

This project is a small distortion pedal made with transistors.
It takes the sound from an electric guitar and changes it to make a distorted tone that works well with rock and experimental music. The pedal uses a high-gain NPN transistor to boost the signal and diodes to clip the waveform, which creates the distortion effect. It runs on a 9V DC power supply and has a 3PDT footswitch for switching between bypass and distortion mode. There's also an LED light that shows if the pedal is on.

The project includes a custom-designed PCB made in KiCad, wires for the footswitch, audio jacks, and power input, and a 3D layout for the enclosure.

It is really simple to use it too:

To use the pedal, connect your electric guitar to the input jack and plug the output jack into an amplifier.
Then, connect a 9V DC power supply to the pedal.

When you press the 3PDT footswitch, it turns the pedal on or off.
When it's on, the LED lights up and the signal goes through the distortion circuit, changing the sound to a distorted tone. When it's off, the signal goes straight from input to output without any change.

Wondering why i made this project?
I made this project to learn about analog audio electronics and guitar effects.
The main aim was to understand how transistor amplification, biasing, and diode clipping affect the guitar signal to create distortion.

Building the pedal also helped me learn how to design PCBs in KiCad, wire hardware, and layout enclosures.
Instead of just copying an existing pedal, I created my own design and layout to better understand the whole process of building a pedal from a circuit diagram to the final product.

Images:

PCB Layout

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/pcb.png)


CAD Enclosure


![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/enclosure%20body.png)

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/enclosure%20bottom.png)


Wiring 

The wiring labels on the board indicate the following:

InG - Intended for input jack ground
In - Input Jack Signal
SW - Switch connection to footswitch
SwG - Ground connection to footswitch
O - Output Jack Signal
OG - Intended for output jack ground
Gnd - Intended for power jack ground
9v - Positive 9v power

Note: The pedal wiring works the same as most PedalPCB pedals with a 3PDT footswitch unless otherwise noted. You can use this  [this build documentation](https://docs.pedalpcb.com/project/Amentum.pdf) build documentation as a wiring reference.

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/Screenshot%202026-03-06%20004447.png)

List Of Material 

[Click Here](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/BOM.csv)

RESISTORS (1/4 watt)

| QTY | VALUE |

| 1 | 390 ohm |

| 1 | 4K7 |

| 1 | 10K |

| 1 | 43K |

| 1 | 430K |




CAPACITORS

| QTY | VALUE |

| 2 | 0.1 UF (100nF) |



TRANSISTORS

| QTY | Part # |

| 1 | 2N5088 |



DIODES

| QTY | Part # |

| 1 | 1N5817 |

| 1 | 5mm LED (color of choice) | Note: Tayda drill template assumes the LED is in a 5mm bezel, change LED hole size as desired.



POTENTIOMETERS

| QTY | VALUE |

| 1 | A100K | Note: B100K for linear taper works fine. Use 16mm right angle PCB mount if using 1590a drill template.



SWITCHES

1 | 3DPDT footswitch


JACKS

2 | 1/4" Mono Audio Jack

1 | 9 volt power jack (center negative) Note: No space for battery in 1590a enclosure

