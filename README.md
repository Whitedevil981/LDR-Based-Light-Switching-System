# LDR-Based-Light-Switching-System
# Project Objective:
To design a light control system that automatically turns on a street light (or any light source) when it becomes dark and turns it off when there is sufficient daylight, using an LDR (Light Dependent Resistor) and basic electronic components.
# Working Principle:
The system is based on the light-sensing capability of an LDR. An LDR changes its resistance based on the intensity of light falling on it:

Bright light = low resistance

Darkness = high resistance

This change in resistance alters the voltage in a voltage divider circuit, which is used to switch a transistor. The transistor acts as an electronic switch to turn a relay or LED on or off.
# What the Basic PBC Circuit Includes:

LDR as light sensor

NPN Transistor 

LED/light bulb

Resistors 

Power supply (Battery)

# How It Works:
In daylight, the LDR has low resistance, so the transistor stays OFF → light/bulb is OFF.

At night or in darkness, LDR resistance increases, providing a base current to the transistor.

Transistor turns ON, activating the relay (or lighting up an LED/bulb).

The light remains ON until daylight is detected again.

# Applications:

Street lighting automation
