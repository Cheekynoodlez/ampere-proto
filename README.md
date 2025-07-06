# Ampere Repo v1

This repo is intended for all of the code used to run and maintain Ampere v1, as well as track each step of the process and keep a timeline while he is still in progress.

## Primary To-Do List:

- [x] Set up README.md
- [ ] Get the RPI RGB LED Matrix hardware/software functional
- [ ] Figure out the mess of wiring and thermals for RPI and sensors
- [ ] Fan controls
- [ ] Trigger expressions/expression control from Ampere Repo
- [ ] Find a way to easily upload animations/expressions
- [ ] Set up script for cycling animations

## Secondary To-Do List (May be omitted):

- [ ] Voice reactivity
- [ ] Heat/Humidity detection for user safety
- [ ] Bluetooth connectivity (RPI and a web app)
- [ ] Games (Tetris, DOOM)
- [ ] Voice modulation for audio affect


## Hardware, software and background info

For this project, I am running a Raspberry Pi 4 with an Adafruit matrix bonnet and two Adafruit 64x32 RGB LED Matrices, 3mm pitch. At this point, the foundation of the plan is to use [Hzeller's rpi rgb led matrix library](https://github.com/hzeller/rpi-rgb-led-matrix) in combination with a python script to cycle between animations.
